# Security policy

## Reporting a problem

If you find a security problem in this repository (for example a workflow or script that does something it shouldn't, a file that contains personal data, or a link that leads somewhere unsafe), please **do not open a public issue**. Use **Security → Report a vulnerability** on this repository's GitHub page instead. Only the maintainer sees the report.


You can expect a first answer within 14 days.

## What is in scope

- the scripts in `scripts/` and `tools/` (Python standard library only, they connect only to `127.0.0.1`),
- the workflow files (`workflows/`) – they use built-in ComfyUI nodes only,
- the images and templates in this repository.

AI models and ComfyUI itself are **not** part of this repository – report problems with them to their authors.

## Safe use

- Download the files only from this repository (`github.com/matthew-flake/...`). Copies posted elsewhere may be modified.
- Check the files with `SHA256SUMS.txt` if you received them from someone else.
- Download models only from the official sources listed in `MODELS.md`, always as `.safetensors`.
- Install ComfyUI extensions only through the Manager and only when you need them (see the book, chapter 9).
- Never run ComfyUI or the scripts with administrator rights.

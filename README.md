# Node by Node – companion pack (edition 10.26)

Free companion files for the book *Node by Node. ComfyUI from Your First Image to Your Own Workflow* (Matthew Flake, edition 10.26, October 2026). No account, no e-mail.

![Results](docs/results.jpg)

## Start in 3 steps
1. Download the models listed in `MODELS.md` into `ComfyUI/models/...`.
2. Copy `inputs/*.png` to `ComfyUI/input`.
3. Drag a file from `workflows/ui` onto the ComfyUI window and click **Run**.

## Contents
| Folder | What |
|---|---|
| `workflows/ui` | 11 workflows – drag & drop (built-in nodes only) |
| `workflows/api` | the same in API format for scripts |
| `inputs` | exercise images |
| `scripts` | `series.py` + `topics.csv` – batch series (chapter 15) |
| `materials` | checklists, notes template, licence register, brief and offer templates |
| `docs/graphs` | screenshots of every graph |
| `samples` | test results as PNG with embedded workflow |
| `TESTED.md` | test report (RTX 5060 8 GB) |

| # | File | Chapter |
|---|---|---|
| W01 | [first_image](workflows/ui/W01_first_image.json) · [graph](docs/graphs/W01_graph.jpg) | 3 |
| W02 | [cfg_test](workflows/ui/W02_cfg_test.json) · [graph](docs/graphs/W02_graph.jpg) | 5 |
| W03 | [img2img_denoise](workflows/ui/W03_img2img_denoise.json) · [graph](docs/graphs/W03_graph.jpg) | 6 |
| W04 | [inpainting_mask](workflows/ui/W04_inpainting_mask.json) · [graph](docs/graphs/W04_graph.jpg) | 7 |
| W05 | [outpainting_panorama](workflows/ui/W05_outpainting_panorama.json) · [graph](docs/graphs/W05_graph.jpg) | 7 |
| W06 | [upscale_2x](workflows/ui/W06_upscale_2x.json) · [graph](docs/graphs/W06_graph.jpg) | 8 |
| W07 | [hires_fix](workflows/ui/W07_hires_fix.json) · [graph](docs/graphs/W07_graph.jpg) | 8 |
| W08 | [controlnet_canny](workflows/ui/W08_controlnet_canny.json) · [graph](docs/graphs/W08_graph.jpg) | 10 |
| W09 | [lora_comparison](workflows/ui/W09_lora_comparison.json) · [graph](docs/graphs/W09_graph.jpg) | 11 |
| W10 | [all_together](workflows/ui/W10_all_together.json) · [graph](docs/graphs/W10_graph.jpg) | 13 |
| W11 | [series](workflows/ui/W11_series.json) · [graph](docs/graphs/W11_graph.jpg) | 15 |

Integrity: `SHA256SUMS.txt`. Regenerate the workflows: `python tools/node_by_node.py workflows` (writes `workflows/ui` and `workflows/api`). Licences: see `LICENSE.md`. Workflows and scripts – MIT. Models are not included.
Not affiliated with Comfy Org or Stability AI.

# Opening the Black Box

[![DOI](https://zenodo.org/badge/1325906591.svg)](https://doi.org/10.5281/zenodo.21835864)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](LICENSE)

A free, self-paced course in explainable AI for large language models, by [Hadi Mohammadi](https://mohammadi.cv). Cite it via DOI [10.5281/zenodo.21835864](https://doi.org/10.5281/zenodo.21835864).

- **Take the course:** https://mohammadi.cv/opening-the-black-box/
- **Lab notebooks** (MIT licensed, separate repository): https://github.com/mohammadi-hadi/hands-on-xai-labs

Five days of guided material built on thirteen open notebooks that run in your browser on a free GPU. Each day tells you what the method is for, sends you into the lab, and names the number to look for when it finishes. Nothing to install.

| Day | Topic | Labs |
| --- | --- | --- |
| 1 | Why models need explaining | ch01, ch02 |
| 2 | The instruments: feature attribution and attention | ch04, ch05 |
| 3 | Build it, break it: probing, counterfactuals, explanation-guided attacks | ch06, ch07 |
| 4 | Trust and evaluation: faithfulness, LLM judges, chain-of-thought | ch08, ch09 |
| 5 | Inside the model: mechanistic interpretability, then production | ch10, plus ch11–ch13 |

## What is in this repository

| Path | What it is |
| --- | --- |
| `docs/` | The course page, served by GitHub Pages at the address above |
| `materials.enc` | The materials bundle for the instructor-led school, AES-256-GCM encrypted; it decrypts in the browser with the access code |
| `CITATION.cff`, `.zenodo.json` | Citation and archive metadata |

The notebooks themselves are not here. They live in [hands-on-xai-labs](https://github.com/mohammadi-hadi/hands-on-xai-labs) and are archived at [10.5281/zenodo.21804605](https://doi.org/10.5281/zenodo.21804605).

## Bring the full school to your institution

The instructor-led edition is a five-day school: morning lectures, afternoon labs, a red-team challenge, and a capstone in which teams audit a model of their own and present the findings. [Details and contact](https://mohammadi.cv/opening-the-black-box/#bring).

## Citation

If this course is useful in your teaching or research, please cite it (see [CITATION.cff](CITATION.cff)):

```bibtex
@misc{mohammadi_opening_the_black_box,
  author    = {Mohammadi, Hadi},
  title     = {Opening the Black Box: a free, self-paced course in explainable {AI} for large language models},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.21835864},
  url       = {https://mohammadi.cv/opening-the-black-box/}
}
```

That DOI resolves to whichever version is current; [10.5281/zenodo.21835865](https://doi.org/10.5281/zenodo.21835865) pins v1.0.0.

When it is the notebooks you used rather than the course, cite the labs instead: [10.5281/zenodo.21804605](https://doi.org/10.5281/zenodo.21804605).

## Rights

Course text and page design © 2026 Hadi Mohammadi, released under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/): share it with attribution, but no commercial use and no derivatives. The full terms are in [LICENSE](LICENSE). The encrypted bundle (`materials.enc`) is for participants of a hosted edition; all rights reserved. The lab notebooks the course is built on are MIT licensed in [their own repository](https://github.com/mohammadi-hadi/hands-on-xai-labs).

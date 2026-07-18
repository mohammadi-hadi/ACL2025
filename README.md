<div align="center">

# Assessing the Reliability of LLMs Annotations — Project Page

[![arXiv](https://img.shields.io/badge/arXiv-2507.13138-b31b1b.svg)](https://arxiv.org/abs/2507.13138)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

*Project website for the GeBNLP @ ACL 2025 paper on the reliability of LLM annotations for sexism detection.*

**Live site:** [mohammadi-hadi.github.io/ACL2025](https://mohammadi-hadi.github.io/ACL2025/)

</div>

## Paper

|                  |                                                                          |
| ---------------- | ------------------------------------------------------------------------ |
| **Title**        | Assessing the Reliability of LLMs Annotations in the Context of Demographic Bias and Model Explanation |
| **Authors**      | Hadi Mohammadi, Tina Shahedi, Pablo Mosteiro, Massimo Poesio, Ayoub Bagheri, Anastasia Giachanou |
| **Affiliation**  | Utrecht University; Queen Mary University of London |
| **Venue**        | 6th Workshop on Gender Bias in Natural Language Processing (GeBNLP), ACL 2025 |
| **arXiv**        | [2507.13138](https://arxiv.org/abs/2507.13138) |
| **Code**         | [Explainable_Annotations_Reliability](https://github.com/mohammadi-hadi/Explainable_Annotations_Reliability) |

## Overview

This repository holds the static project page for the paper, which examines how reliable LLM-generated annotations are for sexism detection, analyzing demographic bias and model explanations with mixed-effects models and comparing generative models against a fine-tuned BERT baseline.

The page itself is plain HTML/CSS/JavaScript built on the Bulma-based academic project page template, and includes the paper PDF, result figures, abstract, and citation.

## Citation

```bibtex
@inproceedings{mohammadi2025assessing,
  title={Assessing the Reliability of LLMs Annotations in the Context of Demographic Bias and Model Explanation},
  author={Mohammadi, Hadi and Shahedi, Tina and Mosteiro, Pablo and Poesio, Massimo and Bagheri, Ayoub and Giachanou, Anastasia},
  booktitle={The 6th Workshop on Gender Bias in Natural Language Processing},
  pages={92},
  year={2025}
}
```

## Quick Start

The site is fully static and is deployed to GitHub Pages by the workflow in `.github/workflows/static.yml` on every push to `main`. To preview locally:

```bash
git clone https://github.com/mohammadi-hadi/ACL2025.git
cd ACL2025
python3 -m http.server 8000
# then open http://localhost:8000
```

## Repository Structure

```
ACL2025/
├── index.html                 # The project page
├── static/
│   ├── css/                   # Bulma and page styles
│   ├── js/                    # Carousel/slider scripts
│   ├── images/                # Figures and logos
│   └── ACL2025.pdf            # Paper PDF
├── .github/workflows/         # GitHub Pages deployment
└── README.md                  # This file
```

## Related Work

- [Explainable_Annotations_Reliability](https://github.com/mohammadi-hadi/Explainable_Annotations_Reliability) — code repository for this paper
- [Explainable-Sexism-Detection](https://github.com/mohammadi-hadi/Explainable-Sexism-Detection) — transparent sexism-detection pipeline with SHAP explanations (Applied Sciences, 2024)

## License

Released under the MIT License — see [LICENSE](LICENSE). Bundled third-party assets (Bulma, Font Awesome, carousel/slider plugins) keep their own licenses.

## Contact

- **Hadi Mohammadi** — Utrecht University
- Website: [mohammadi.cv](https://mohammadi.cv)

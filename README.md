# Assessing the Reliability of LLMs Annotations — Project Page

Project website for the paper "Assessing the Reliability of LLMs Annotations in the Context of Demographic Bias and Model Explanation", presented at the 6th Workshop on Gender Bias in Natural Language Processing (GeBNLP) at ACL 2025.

Live site: https://mohammadi-hadi.github.io/ACL2025/

## Overview

This repository holds the static project page for the paper by Hadi Mohammadi, Tina Shahedi, Pablo Mosteiro, Massimo Poesio, Ayoub Bagheri, and Anastasia Giachanou (Utrecht University; Queen Mary University of London). The paper examines how reliable LLM-generated annotations are for sexism detection, analyzing demographic bias and model explanations with mixed-effects models and comparing generative models against a fine-tuned BERT baseline.

The page itself is plain HTML/CSS/JavaScript built on the Bulma-based academic project page template, and includes the paper PDF, result figures, abstract, and citation. Paper preprint: https://arxiv.org/abs/2507.13138

## Repository structure

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

## How to run

The site is fully static and is deployed to GitHub Pages by the workflow in `.github/workflows/static.yml` on every push to `main`. To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

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

## License

Released under the MIT License. See [LICENSE](LICENSE) for details. Bundled third-party assets (Bulma, Font Awesome, carousel/slider plugins) keep their own licenses.

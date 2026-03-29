<div align="center">

# :mag: Explainable AI (XAI)

### Making black-box models transparent -- SHAP, LIME, and beyond

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![SHAP](https://img.shields.io/badge/SHAP-0.42+-B721FF?style=for-the-badge&logo=python&logoColor=white)](https://shap.readthedocs.io)
[![LIME](https://img.shields.io/badge/LIME-0.2+-FF6F00?style=for-the-badge&logo=python&logoColor=white)](https://github.com/marcotcr/lime)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## Overview

This repository is a portfolio of Explainable AI (XAI) projects focused on model interpretability and transparency. As AI systems are deployed in high-stakes domains like healthcare, finance, and criminal justice, understanding *why* a model makes a prediction is just as important as the prediction itself.

Each project demonstrates practical techniques for opening the black box -- from feature importance and partial dependence plots to SHAP values and counterfactual explanations.

## Topics Covered

| # | Topic | Techniques | Status |
|---|-------|-----------|--------|
| 1 | **Feature Importance** | Permutation importance, impurity-based importance | :hourglass: Planned |
| 2 | **SHAP (SHapley Additive exPlanations)** | TreeSHAP, KernelSHAP, DeepSHAP, force/summary plots | :hourglass: Planned |
| 3 | **LIME (Local Interpretable Model-agnostic Explanations)** | Tabular, text, and image explanations | :hourglass: Planned |
| 4 | **Partial Dependence Plots (PDP)** | PDP, ICE plots, ALE plots | :hourglass: Planned |
| 5 | **Counterfactual Explanations** | DiCE, Alibi, what-if analysis | :hourglass: Planned |
| 6 | **Attention Visualization** | Transformer attention maps, Grad-CAM | :hourglass: Planned |
| 7 | **Surrogate Models** | Global surrogates, rule extraction | :hourglass: Planned |
| 8 | **Fairness & Bias Detection** | Disparate impact, equalized odds, AIF360 | :hourglass: Planned |
| 9 | **Model-Specific Interpretability** | Linear model coefficients, decision tree paths | :hourglass: Planned |
| 10 | **XAI for Deep Learning** | Integrated gradients, saliency maps, GradCAM++ | :hourglass: Planned |

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Core language |
| SHAP | Shapley-based model explanations |
| LIME | Local surrogate explanations |
| scikit-learn | ML models for demonstration |
| XGBoost / LightGBM | Gradient boosting models |
| Matplotlib / Seaborn | Visualization |
| Alibi | Counterfactual explanations |
| AIF360 | Fairness & bias toolkit |
| Jupyter Notebook | Interactive development |

## Project Structure

```
Explainable_AI_-XAI-/
|-- README.md
|-- shap_explanations/         # (planned) SHAP analysis projects
|-- lime_explanations/         # (planned) LIME analysis projects
|-- feature_importance/        # (planned) Permutation & impurity importance
|-- partial_dependence/        # (planned) PDP, ICE, ALE plots
|-- counterfactuals/           # (planned) Counterfactual explanation projects
|-- attention_visualization/   # (planned) Transformer attention & Grad-CAM
|-- fairness_bias/             # (planned) Fairness auditing projects
|-- deep_learning_xai/         # (planned) Saliency maps, integrated gradients
```

## Getting Started

### Prerequisites

```bash
pip install shap lime scikit-learn xgboost lightgbm matplotlib seaborn alibi jupyter
```

### Running Notebooks

```bash
jupyter notebook
```

Navigate to the topic folder of interest and open the corresponding `.ipynb` file.

## Roadmap

- [ ] SHAP deep-dive: TreeSHAP on XGBoost model
- [ ] LIME explanations for tabular and text data
- [ ] Feature importance comparison (permutation vs. impurity)
- [ ] Partial dependence and ICE plot tutorial
- [ ] Counterfactual explanations with DiCE
- [ ] Grad-CAM visualization for CNN predictions
- [ ] Fairness audit on a real-world dataset
- [ ] End-to-end XAI pipeline for a production model

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Part of the [DatariusAI](https://github.com/DatariusAI) organization**

</div>

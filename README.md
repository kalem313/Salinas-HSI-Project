# Hyperspectral Image Analysis – Salinas Dataset

This project was developed as part of the MSc in Data Science at AUEB for the course **Machine Learning and Computational Statistics**.

It focuses on two main tasks using a hyperspectral image of the Salinas Valley:
- **Spectral Unmixing** using five methods
- **Supervised Classification** using four classifiers

---

## Project Contents

| File                                      | Description                                      |
|-------------------------------------------|--------------------------------------------------|
| `Project_AUEB_KalemkeridisEvangelos.ipynb` | Jupyter notebook with code, analysis & results   |
| `Project - Machine Learning and Computational Statistics.pdf` | Original project description & requirements |

---

## Objectives

### 1. **Spectral Unmixing**
Estimate sub-pixel composition (abundance vectors) using:
- Ordinary Least Squares (OLS)
- OLS with sum-to-one constraint
- OLS with non-negativity constraint
- OLS with both constraints
- LASSO (sparse regression)

Each method is compared using:
- Abundance maps
- Reconstruction error across pixels

### 2. **Supervised Classification**
Classify image pixels into known categories using:
- Naive Bayes
- k-Nearest Neighbors
- Minimum Euclidean Distance (custom)
- Bayesian classifier (Gaussian)

Performance metrics:
- 10-fold cross-validation
- Confusion matrices
- Classification accuracy

---

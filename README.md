# Titanic Survival Prediction

A machine-learning project exploring the Titanic dataset and building a reproducible passenger-survival prediction workflow.

## Objective

Predict whether a passenger survived using demographic and travel-related features while practicing the complete tabular machine-learning workflow.

## ML Workflow

1. Load and inspect the dataset
2. Explore distributions and missing values
3. Prepare numerical and categorical features
4. Train a classification model
5. Evaluate predictions and model behavior

## Tech Stack

**Python · pandas · NumPy · scikit-learn · Matplotlib · Jupyter · uv**

## Repository Structure

```text
Titanic-Dataset.csv    Dataset used for analysis
titanic.ipynb          Exploratory analysis and ML workflow
pyproject.toml         Project metadata and dependencies
uv.lock                Reproducible dependency lockfile
src/                   Python package source
```

## Getting Started

This project uses `uv` for environment and dependency management.

```bash
uv sync
```

Then open `titanic.ipynb` in Jupyter or VS Code and run the notebook cells in order.

## What This Project Demonstrates

- Data cleaning and preprocessing
- Exploratory data analysis
- Feature preparation for tabular ML
- Classification with scikit-learn
- Model evaluation
- Reproducible Python environment management

## Next Improvements

- Compare multiple classification algorithms
- Add cross-validation and systematic hyperparameter tuning
- Report precision, recall, F1 score and ROC-AUC
- Add feature-importance analysis
- Convert preprocessing and training into reusable pipelines

---

**Focus:** Machine Learning · Classification · Data Preprocessing · Exploratory Data Analysis

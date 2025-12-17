# Spaceship Titanic Challenge

## Overview

This project addresses Kaggle’s **Spaceship Titanic** classification challenge, where the goal is to predict whether passengers were transported to an alternate dimension after a spacetime anomaly.

We started with Kaggle’s baseline Random Forest model and improved performance through better preprocessing and hyperparameter tuning.

## What We Did

- Reproduced Kaggle’s baseline Random Forest model
- Reimplemented the model using **Scikit-learn**
- Applied:
  - One-hot encoding for categorical features
  - Feature scaling for numerical features
  - Mean/mode imputation for missing values
- Used stratified train-test splitting and a fixed random seed
- Tuned hyperparameters using `RandomizedSearchCV`

## Results

- **Baseline accuracy:** 78.653%
- **Improved accuracy:** **79.752%**

## Files

- `baseline.ipynb` – Kaggle tutorial baseline model
- `improved.ipynb` – Improved model with preprocessing and tuning
- `group_2_project_report.pdf` – Full project report

## References

- Kaggle, *Spaceship Titanic Competition*.  
[Kaggle Spaceship Titanic Competition](https://www.kaggle.com/competitions/spaceship-titanic/overview)

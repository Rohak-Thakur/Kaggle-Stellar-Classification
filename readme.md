# Kaggle Stellar Classification

Solution for the Kaggle Playground Series S6E6 — Stellar Class Prediction.

## Problem
Predict whether an astronomical object is a GALAXY, STAR, or QSO (Quasar)
based on photometric and spectral measurements from the SDSS survey.

## Dataset Features
- `alpha`, `delta` — sky coordinates
- `u`, `g`, `r`, `i`, `z` — photometric brightness bands
- `redshift` — most predictive feature
- `spectral_type` — stellar spectral classification
- `galaxy_population` — galaxy morphology category

## Metric
Balanced Accuracy Score

## Approach
1. EDA with Tableau and pandas
2. Decision Tree baseline
3. XGBoost main model
4. LightGBM comparison
5. Ensemble

## Results
_To be updated_
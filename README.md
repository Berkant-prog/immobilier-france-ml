# Real Estate Price Prediction – France (DVF)

Machine Learning project based on the French DVF open dataset.

## Objective
Predict apartment prices in Île-de-France using Machine Learning.

## Dataset
- Source: data.gouv.fr (DVF – Demande de Valeur Foncière)
- Data cleaned and filtered (apartments only, IDF)
- Raw CSV not included in repository

## Methodology
- Data cleaning and feature engineering
- Log-transformed target variable
- Baseline: Linear Regression
- Final model: Random Forest Regressor
- Evaluation: R² and MAE

## Results
- Significant improvement over baseline
- Error factor reduced to ~1.4–1.5
- Feature importance analysis confirms market logic

## Tech Stack
- Python
- pandas / numpy
- scikit-learn
- matplotlib

## Author
ESIEE Paris – Data & AI track

# Recidivism Prediction Model
## Project Overview
This project builds a machine learning model to predict recidivism in Chicago, leveraging demographic, geographic, and historical crime data. Understanding factors influencing repeat offenses can inform interventions and potentially reduce recidivism rates.

## Data
The model utilizes two datasets:

1. Sentencing Data (CSV): Contains information about defendants (age, race, gender, offense, arrest date, sentencing).
2. Diversion Program Data (CSV): Details participation in diversion programs (referral dates, program types, outcomes).

## Methodology

### Data Cleaning and Preprocessing

- Remove unnecessary columns.
- Handle missing values.
- Create informative features (feature engineering).
- Encode categorical variables (one-hot, ordinal).
- Identify and address outliers.

## Feature Selection

Analyze feature importance (correlation, model scores).
Select relevant features for improved performance and reduced dimensionality.

## Model Training

Use Random Forest Classifier as the baseline model.
Fine-tune hyperparameters (GridSearchCV, RandomizedSearchCV) for optimal performance.
Consider alternative algorithms (Logistic Regression, Support Vector Machines, XGBoost) for comparison.

## Model Evaluation

Assess model performance metrics (accuracy, precision, recall, F1-score, AUC-ROC).
Evaluate on training and testing sets to identify overfitting or underfitting.
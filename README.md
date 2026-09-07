# Predicting-Accident-Severity
## Project Overview
Predicting reported road collision severity in Great Britain using 2024 road safety data, machine learning and Explainable AI (XAI), with data preprocessing, class-imbalance handling, model comparison, hyperparameter optimisation, and SHAP-based interpretation.

## Dataset
The project uses three 2024 road safety datasets published by the UK Department for Transport:
- Collision dataset
- Vehicle dataset
- Casualty dataset

## Data Preparation
Data preprocessing included data integration, duplicate removal, missing-value handling, data type correction, invalid-value removal and feature engineering.

## Exploratory and Statistical Analysis
Cramér's V was used to examine associations between categorical variables, while Pearson correlation was used to examine relationships between numerical variables. Feature distributions were also visualised against collision severity.

## Class Imbalance
The target variable was highly imbalanced, with Slight collisions representing the majority class. SMOTE-NC was therefore used to generate synthetic samples for minority classes. SMOTE-NC was incorporated into the modelling pipeline and applied only to the training data to prevent data leakage.

## Machine Learning Models
- Ordinal Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Explainable AI
Explainable AI techniques were applied using SHAP (SHapley Additive exPlanations) to investigate the contribution of individual features to model predictions.

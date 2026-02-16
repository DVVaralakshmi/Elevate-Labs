# AI-ML-Internship-Task-8
## Decision Tree – Bank Marketing Subscription Prediction
## Overview
This project uses a Decision Tree Classifier to predict whether a customer will subscribe to a bank term deposit. The focus is on model interpretability using decision rules.
## Dataset
- Name: Bank Marketing Dataset (UCI via Kaggle)
- File: bank-full.csv
- Size: 45,211 rows × 17 columns
- Target: y (yes / no)
## Tools
- Python
- Pandas
- Scikit-learn
- Matplotlib
## Workflow
1. Load and verify dataset
2. Data preprocessing and encoding
3. Train-test split
4. Train Decision Tree (limited max_depth)
5. Model evaluation
6. Tree visualization
7. Decision rule interpretation
## Model
- Algorithm: Decision Tree Classifier
- Criterion: Gini Impurity
- Overfitting Control: max_depth
## Evaluation
- Training & Testing Accuracy
- Classification Report
## Key Insights
- Successful previous campaigns increase subscription chances
- Longer call duration improves likelihood
- Excessive campaign contacts reduce success

# AI-ML-Internship-Task-9
## Credit Card Fraud Detection using Random Forest
## Project Overview

This project builds a machine learning model to detect fraudulent credit card transactions using the Random Forest algorithm.

It focuses on handling imbalanced data and evaluating performance using Precision, Recall, and F1-score instead of accuracy.

## Tools Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib & Seaborn
- Joblib

## Dataset
The dataset contains transaction records with a target column:
- Class = 0 → Non-Fraud
- Class = 1 → Fraud
- 
The dataset is highly imbalanced.

**Download link** - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Methodology
1. Load and explore dataset.
2. Separate features and target.
3. Perform stratified train-test split.
4. Train Logistic Regression as baseline model.
5. Train Random Forest classifier.
6. Evaluate using Precision, Recall, and F1-score.
7. Plot feature importance.
8. Save trained model as .pkl file.

## Final Outcome
The project helps in learning ensemble learning and handling imbalanced datasets while building a practical fraud detection system.

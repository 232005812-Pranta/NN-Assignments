Problem Set 02: Bank Marketing Term Deposit Prediction using Logistic Regression

Overview
This directory contains the solution for Problem Set 02, aiming to predict whether a banking customer will subscribe to a term deposit (`yes` or `no`) based on demographic and operational interaction features.

Methodology
- Data Preprocessing: Cleaned metadata artefacts, mapped target labels to binary indicators (`yes`: 1, `no`: 0), and applied One-Hot Encoding to categorical attributes.
- Feature Scaling & Splitting: Applied `StandardScaler` to ensure balanced feature weight distribution and split the dataset into 80% training and 20% test sets with stratification.
- Model: Trained a Logistic Regression classifier (`max_iter=1000`).

 Model Findings & Results
- Overall Accuracy: ~90%
- Evaluation Metrics: ROC-AUC Score and Confusion Matrix demonstrate solid discrimination capability on unseen customer data.

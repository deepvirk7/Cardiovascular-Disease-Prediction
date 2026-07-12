# Cardiovascular-Disease-Prediction
The primary goal of this project is to build a robust machine learning classification pipeline capable of predicting the likelihood of cardiovascular disease in patients. By analyzing structured medical data—such as age, clinical symptoms, and blood test results—the model assists in early diagnosis and proactive healthcare management.

Methodology & Approach

Data Preprocessing: The dataset is partitioned using stratified sampling to maintain the exact ratio of healthy to diseased patients across training and testing sets. Feature scaling (Standardization) is applied to ensure metrics with vastly different ranges (e.g., cholesterol levels vs. age) are weighted equally by distance-based algorithms.

Algorithmic Comparison: The project implements and evaluates four distinct classification models to find the optimal fit for complex medical data:

Logistic Regression (Baseline linear model)

Random Forest (Ensemble tree-based model)

Support Vector Machine (SVM) (High-dimensional boundary mapping)

XGBoost (Advanced gradient boosting)

Diagnostic Evaluation: In a healthcare context, a False Negative (failing to identify a sick patient) is highly dangerous. Therefore, the models are evaluated not just on raw Accuracy, but heavily on Recall (Sensitivity) and the ROC-AUC score to ensure maximum detection capability.

Technology Stack

Language: Python

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-Learn, XGBoost

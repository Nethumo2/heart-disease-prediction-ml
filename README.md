Heart Disease Prediction Using Machine Learning

University AI/ML Project | UCI Heart Disease Dataset
My Role: SVM Model Developer (Training, Optimization & Evaluation)

📌 Project Overview

This project focuses on predicting heart disease using multiple machine learning algorithms and analyzing model performance, bias, and fairness. The dataset contains 1,025 patient records with 13 clinical features.

We implemented five ML models:

Logistic Regression

Support Vector Machine (SVM) ← my contribution

Decision Tree

K-Nearest Neighbors (KNN)

Neural Network (MLP)

🎯 Purpose

Improve early prediction of heart disease using ML

Compare multiple algorithms for performance

Ensure ethical, transparent, and fair AI practices

Understand how clinical variables influence predictions

🛠 My Contribution (SVM Model Developer)

I was responsible for:

Applying StandardScaler to numerical features

Training SVM with linear, RBF, and polynomial kernels

Tuning C and gamma using GridSearchCV

Performing 5-fold cross-validation

Evaluating accuracy, precision, recall, F1-score, ROC-AUC

Comparing SVM results with other models

My SVM Results

Accuracy: 0.80

F1-Score: 0.84

Recall: 0.92

Best Kernel: Polynomial

📊 Final Results (Model Comparison)
Model	Accuracy	F1-Score	ROC-AUC
Logistic Regression	0.86	0.89	0.86
SVM	0.80	0.84	0.73
Decision Tree	0.84	0.87	0.81
KNN	0.84	0.88	0.85
Neural Network	0.82	0.86	0.85

Best Overall Model: Logistic Regression
Best Recall: SVM (detects disease cases well)

🧹 Preprocessing Steps

Duplicate removal

Handling missing values

Encoding categorical variables

Outlier removal (IQR method)

Feature scaling (StandardScaler)

Correlation analysis

Feature selection

🧠 Lessons Learned

Hyperparameter tuning significantly changes model outcomes

Simpler models can outperform complex ones

Ethical and fairness checks are essential in healthcare ML

Feature quality impacts performance more than quantity

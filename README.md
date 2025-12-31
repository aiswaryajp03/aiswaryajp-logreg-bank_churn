# aiswaryajp-logreg-bank_churn
Project Overview
This project implements a Logistic Regression model to solve a binary classification problem. The model predicts class labels based on input features and evaluates performance using standard classification metrics such as the Confusion Matrix, ROC Curve, and AUC score. The project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and visualization.

Dataset Specifications
The dataset consists of labeled observations used for binary classification.

Key Components:
Input Features: Numerical attributes used as predictors
Target Variable: Binary class label (0 or 1)
Dataset Split: Training and testing subsets

Logistic Regression Model
Logistic Regression is a supervised learning algorithm used for binary classification. Instead of predicting continuous values, it estimates the probability that a given instance belongs to the positive class.
Model Equation
The model uses the logistic (sigmoid) function:

The very basic equation for logistic regression is:

𝑦=1/[1+(𝑒)^−(𝑤𝑥+𝑏)]

	​

Model Performance

The model is evaluated on the test dataset using the following metrics:

Confusion Matrix

The confusion matrix summarizes prediction results:

True Positives (TP): Correctly predicted positive cases

True Negatives (TN): Correctly predicted negative cases

False Positives (FP): Incorrectly predicted positives

False Negatives (FN): Incorrectly predicted negatives

This matrix helps identify the types of errors made by the model.

ROC Curve

The Receiver Operating Characteristic (ROC) curve plots the True Positive Rate (TPR) against the False Positive Rate (FPR) across different thresholds.

A curve closer to the top-left corner indicates better performance

The diagonal line represents random guessing

AUC Score

The Area Under the Curve (AUC) measures the model’s ability to distinguish between classes.

AUC = 0.5: No discrimination

0.7 – 0.8: Acceptable performance

0.8 – 0.9: Strong performance

> 0.9: Excellent performance

An AUC of 0.83 indicates strong discriminative capability.

Evaluation Results

The project includes the following evaluation assets:

ROC Curve Plot: Visualizes model performance across thresholds

Confusion Matrix Heatmap: Displays classification results

Prediction Output: Comparison of actual vs predicted labels

Implementation Notebook: Full workflow from preprocessing to evaluation


# Bug Severity Classification

Text classification pipeline that predicts software bug severity from bug report text. Built for the CS412 Machine Learning course (Sabancı University) as part of the team "Predictive Pioneers," submitted to an in-class Kaggle competition.

## Overview
- **Features:** TF-IDF and BERT-based embeddings
- **Models tested:** Random Forest, XGBoost, LightGBM, AdaBoost, SVM, CNN
- **Class imbalance:** handled with SMOTE
- **Final model:** Random Forest, selected as the best-performing approach

## My Contribution
This code covers the Random Forest training pipeline, including stratified k-fold cross-validation and SMOTE-based class rebalancing across severity categories.

## Result
Team placed 23rd out of 42 in the course Kaggle competition.

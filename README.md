# bankruptcy-prediction-ml
A machine learning project for bankruptcy prediction using classification models. The dataset includes financial indicators from 10,716 companies classified as "healthy" or "bankrupt." The project applies preprocessing, hyperparameter tuning, cross-validation, and evaluation metrics  to determine the best-performing model.
# Bankruptcy Prediction Using Machine Learning

## Overview
This project focuses on **predicting company bankruptcy** using **machine learning classification models**. It analyzes financial indicators from **10,716 companies**, classifying them as either **healthy** or **bankrupt**.

## Features
- **Data Preprocessing:** Handling missing values, feature scaling (Min-Max Normalization)
- **Cross-Validation:** Stratified K-Folds and class balancing techniques
- **Classification Models Tested:**
  - k-Nearest Neighbors (kNN)
  - Support Vector Machines (SVM)
  - Logistic Regression
  - Decision Trees
  - Random Forests
  - Naive Bayes
  - Linear Discriminant Analysis (LDA)
  - AdaBoost
- **Hyperparameter Tuning:** Performed using **RandomizedSearchCV**
- **Evaluation Metrics:**
  - **F1-score** (Main Metric)
  - Accuracy
  - Precision
  - Recall
  - ROC-AUC
  - Matthews Correlation Coefficient (MCC)
  - Balanced Accuracy

## Dataset
The dataset contains **financial indicators** from 10,716 companies, divided into:
- **Healthy Companies**
- **Bankrupt Companies**

Due to **class imbalance** (97% healthy, 3% bankrupt), **class balancing techniques** such as **undersampling** and **class weighting** were applied.

## Installation
To run the project, install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl

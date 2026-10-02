# Credit Card Fraud Detection using Logistic Regression

A beginner machine learning project that detects fraudulent credit card transactions using Logistic Regression.

The project focuses on understanding the complete binary classification workflow, including exploratory data analysis, class imbalance, feature scaling, model training, evaluation, visualization, and model saving.

## Objective

The objective of this project is to build a Logistic Regression model capable of distinguishing between legitimate and fraudulent credit card transactions.

This project was created primarily to understand the end-to-end machine learning workflow for an imbalanced classification problem.

## Dataset

The project uses the Credit Card Fraud Detection dataset containing anonymized credit card transactions.

The dataset contains:

- **284,807 transactions**
- **492 fraudulent transactions**
- **30 input features**
- **Target:** `Class`
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction

The dataset is loaded directly from an online CSV source in Google Colab. The dataset itself is **not included in this repository**.

## Machine Learning Workflow

```text
Online Dataset
      ↓
Data Exploration
      ↓
Class Distribution Analysis
      ↓
Feature / Target Separation
      ↓
Stratified Train-Test Split
      ↓
Feature Scaling
      ↓
Logistic Regression
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Visualization
      ↓
Model Saving
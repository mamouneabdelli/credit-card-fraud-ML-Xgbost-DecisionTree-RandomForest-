# Credit Card Fraud Detection using Machine Learning

A Machine Learning project for detecting fraudulent credit card transactions using multiple classification algorithms:

- XGBoost
- Random Forest
- Decision Tree

This project uses a Kaggle dataset and compares the performance of different ML models for fraud detection.

---

## Project Overview

Credit card fraud detection is an important real-world machine learning problem where the objective is to classify transactions as:

- Legitimate Transaction
- Fraudulent Transaction

Because fraud cases are rare, the dataset is highly imbalanced, making this a challenging classification task.

This project focuses on:

- Data preprocessing
- Handling imbalanced data
- Training multiple ML models
- Evaluating model performance
- Comparing algorithms

---

## Algorithms Used

### 1. Decision Tree
A simple and interpretable classification algorithm based on tree structures.

### 2. Random Forest
An ensemble learning method that combines multiple decision trees to improve accuracy and reduce overfitting.

### 3. XGBoost
An optimized gradient boosting algorithm known for high performance and excellent results in classification problems.

---

## Dataset

Dataset downloaded from Kaggle:

- Credit Card Fraud Detection Dataset

The dataset contains anonymized transaction features and a target column:

- `0` → Normal Transaction
- `1` → Fraudulent Transaction

---

## Project Structure

```bash
credit-card-fraud-ML/
│
├── dataset/
│   └── creditcard.csv
│
├── notebooks/
│   └── preprocessing.ipynb
│
├── models/
│
├── results/
│
├── README.md
│
└── requirements.txt

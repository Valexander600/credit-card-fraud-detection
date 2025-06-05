# 💳 Credit Card Fraud Detection with Machine Learning
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

# Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

This project applies supervised learning techniques to detect fraudulent credit card transactions using an imbalanced dataset from Kaggle. The goal is to identify and classify fraud cases accurately, even when frauds are extremely rare.

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [Screenshots](#screenshots)

## Overview
This project builds machine learning models to detect fraudulent credit card transactions using the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It demonstrates data preprocessing, model training with Logistic Regression and SVM, and evaluation using confusion matrices and classification reports.

## How to Run

To reproduce the results:

1. Clone the repository:
   ```bash
   git clone https://github.com/Valexander600/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
jupyter notebook



---

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains anonymized features (`V1` to `V28`), `Amount`, and a binary target variable `Class` (1 = Fraud, 0 = Legit).

---

## 📊 Exploratory Data Analysis (EDA)

- Highly imbalanced dataset (~0.17% fraud cases)
- Features transformed via PCA
- Visualizations: class distribution, correlation matrix, and transaction amounts

---

## 🤖 Models Used

- Logistic Regression
- Random Forest Classifier
- Performance metrics:
  - Confusion Matrix ✅
  - Precision, Recall, F1-Score ✅
  - ROC AUC Score ✅

---

## 📈 Model Results

| Model               | Precision | Recall | F1-Score | ROC AUC |
|---------------------|-----------|--------|----------|---------|
| Logistic Regression | 0.91      | 0.74   | 0.81     | 0.97    |
| Random Forest       | 0.93      | 0.76   | 0.84     | 0.98    |

*(Replace these numbers with your actual results)*

---

### 🔍 Modeling 
 - Logistic Regression
- Support Vector Machine (SVM)

### 🧪 ## Evaluation

- Confusion Matrix
- Classification Report

### 📊 Classification Report:

Class	Precision	Recall	F1-Score	Support
0	1.00	1.00	1.00	41534
1	0.84	0.55	0.67	83

Overall accuracy: 1.00


#### Confusion Matrix:
Confusion Matrix:
[[41525     9]
 [   37    46]]


## 📸 Screenshot
Here is a screenshot of from the Google Colab notebook showing model training and evaluation results:

#### Sample Data Preview
![Sample Data](sampledatapreview.png)


---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Valexander600/credit-card-fraud-detection.git
   cd credit-card-fraud-detection

pip install -r requirements.txt
jupyter notebook credit_card_fraud.ipynb

## ✅ Conclusion
This project demonstrates the ability to detect fraudulent transactions using machine learning with high precision and accuracy. Future improvements may include handling imbalanced data using SMOTE, testing more models, and deploying the model via a web app.

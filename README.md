# 💳 Credit Card Fraud Detection with Machine Learning
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

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


---

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains anonymized features (`V1` to `V28`), `Amount`, and a binary target variable `Class` (1 = Fraud, 0 = Legitimate).

---

## 📊 Exploratory Data Analysis (EDA)
- Highly imbalanced dataset (~0.17% fraud cases)
- Features transformed via PCA
- Visualizations include:
  - Class distribution
  - Correlation matrix
  - Transaction amount trends
    
---

## 🤖 Models Used
 - **Algorithms Used:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest Classifier

- **Metrics Evaluated:**
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC AUC Score

---

## 📈 Model Results

| Model               | Precision | Recall | F1-Score | ROC AUC |
|---------------------|-----------|--------|----------|---------|
| Logistic Regression | 0.91      | 0.74   | 0.81     | 0.97    |
| Random Forest       | 0.93      | 0.76   | 0.84     | 0.98    |



---


### 🧪 Evaluation


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

#### Data Preview
![Sample Data](sampledatapreview.png)


---
```markdown
## 🚀 How to Run

1. To reproduce the results, follow these steps:

```bash
git clone https://github.com/Valexander600/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
jupyter notebook credit_card_fraud.ipynb



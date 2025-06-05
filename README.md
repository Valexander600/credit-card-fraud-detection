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

## 🚀 How to Run

1. To reproduce the results, follow these steps:

```bash
git clone https://github.com/Valexander600/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
jupyter notebook credit_card_fraud.ipynb


## ✅ Conclusion
This project demonstrates how machine learning can effectively detect fraudulent credit card transactions, even within highly imbalanced datasets. By applying models like Logistic Regression and Random Forest, we achieved strong precision and accuracy scores, showing potential for real-world fraud detection. While the results are promising, future improvements could include handling class imbalance more robustly (e.g., SMOTE), experimenting with ensemble models like XGBoost, and deploying the solution through a web or API-based application for real-time use.

## 🔮 Future work
To enhance this project and push it toward production-readiness, the following improvements are recommended:

📊 Handle Class Imbalance

Apply techniques like SMOTE, ADASYN, or undersampling to improve fraud case detection.

🚀 Test Advanced Algorithms

Experiment with XGBoost, LightGBM, or CatBoost for better accuracy and efficiency.

🔧 Feature Engineering

Derive new features from Time, Amount, or build domain-specific transformations to improve model performance.

🧠 Model Interpretability

Use SHAP or LIME to explain model predictions and ensure transparency.

🔁 Build ML Pipelines

Automate data preprocessing, model training, and evaluation using scikit-learn pipelines or MLflow.

🌐 Deploy as Web App

Use Flask or FastAPI to create an API, then deploy using Render, Heroku, or AWS.

📈 Monitoring & Alerts

Integrate logging, alerts, and performance monitoring for real-time fraud detection in a production environment.

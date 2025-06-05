# 💳 Credit Card Fraud Detection with Machine Learning

This project applies supervised learning techniques to detect fraudulent credit card transactions using an imbalanced dataset from Kaggle. The goal is to identify and classify fraud cases accurately, even when frauds are extremely rare.

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

## 🖼 Sample Visuals

![Confusion Matrix](images/conf_matrix.png)
![ROC Curve](images/roc_curve.png)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Valexander600/credit-card-fraud-detection.git
   cd credit-card-fraud-detection

pip install -r requirements.txt
jupyter notebook credit_card_fraud.ipynb


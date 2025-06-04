# Credit Card Fraud Detection

## Project Overview

This project is focused on building a machine learning model to predict fraudulent credit card transactions using a real-world dataset. Fraudulent transactions pose a significant challenge to the financial industry, and detecting these transactions in real-time is crucial for minimizing the impact.

The goal of this project is to apply machine learning techniques to classify credit card transactions as either fraudulent or non-fraudulent based on various features, such as transaction amount, user behavior, and more.

## Key Features
- **Data Preprocessing**: The dataset is cleaned and prepared for analysis by handling missing values, encoding categorical features, and normalizing numerical features.
- **Model Implementation**: A Logistic Regression model is used to predict fraudulent transactions.
- **Model Evaluation**: The model’s performance is assessed using common metrics such as accuracy, precision, recall, F1 score, and confusion matrix.
- **Visualization**: Visualizations like confusion matrices and classification report plots are used to help understand the model's performance.

## Dataset

- The dataset contains information about 1259 credit card transactions. Each transaction includes features like `Age`, `Gender`, `Country`, `Transaction Amount`, and `Fraudulent` (target variable).
- The target variable indicates whether the transaction was fraudulent (1) or non-fraudulent (0).

### Dataset Source:
- [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Getting Started

1. **Clone the Repository**:
   To get started with the project, clone the repository to your local machine:
   ```bash
   git clone https://github.com/Valexander600/credit-card-fraud-detection.git

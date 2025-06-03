# Customer Churn Prediction

This project aims to predict whether a customer will **churn (exit)** or **stay**, helping businesses improve their **customer acquisition and retention strategies**. The model uses a **Random Forest Classifier**, trained on customer data, to make predictions with high accuracy.

---

## 📌 Problem Statement

Customer churn is a major concern for companies, as retaining existing customers is more cost-effective than acquiring new ones. The goal of this project is to build a machine learning model that can:

- Accurately predict customer churn.
- Help identify patterns associated with customer exit behavior.
- Support decision-making in customer relationship management.

---

## 🔍 Dataset

- **Source:** [Kaggle - Customer Churn Dataset](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)
- The dataset includes features such as:
  - Customer demographics
  - Account information
  - Transaction behavior
  - Service usage metrics

---

## 🧠 Model Used

- **Algorithm:** Random Forest Classifier  
- An ensemble learning method that builds multiple decision trees and merges them to get more accurate and stable predictions.

---

## 📊 Model Performance

| Metric         | Class 0 (Stay) | Class 1 (Churn) |
|----------------|----------------|-----------------|
| Precision      | 0.91           | 0.97            |
| Recall         | 0.84           | 0.98            |
| F1-Score       | 0.88           | 0.98            |
| Support        | 419            | 2113            |

- **Overall Accuracy:** 96%
- **Macro Avg F1-Score:** 0.93  
- **Weighted Avg F1-Score:** 0.96

---

## 🛠️ Technologies Used

- Python
- scikit-learn
- pandas
- matplotlib / seaborn (for EDA & visualization)
- Jupyter Notebook / Google Colab

---

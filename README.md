# 📉 Customer Churn Prediction

A machine learning project that predicts whether a customer will leave (churn) or stay with a business.  
The aim is to help companies **reduce customer loss** by identifying patterns and taking preventive actions.



## 📝 About

Customer churn is when existing customers stop doing business with a company.  
This project uses **machine learning models** to analyze customer data and predict the likelihood of churn.  

We experiment with multiple algorithms, evaluate their performance, and use insights to reduce churn rates.

---

## 📊 Dataset

- Dataset: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)  
- Contains information about **7,043 customers** from a telecom company.  
- Features include:
  - Demographics (gender, age, etc.)
  - Services subscribed (internet, phone, TV, etc.)
  - Account information (contract type, monthly charges, tenure, etc.)
- Target variable:  
  - `Yes` → Customer churned  
  - `No` → Customer stayed  

---

## ✨ Features

- Data preprocessing (handling missing values, encoding categorical variables, feature scaling)  
- Exploratory Data Analysis (EDA) with visualization  
- Handling class imbalance (SMOTE, class weights)  
- Model training & evaluation: Logistic Regression, Decision Trees, Random Forest, XGBoost, etc.  
- Metrics used: Accuracy, Precision, Recall, F1-score, ROC-AUC  
- Feature importance analysis  

---

## 🛠 Technologies

- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- XGBoost / LightGBM  

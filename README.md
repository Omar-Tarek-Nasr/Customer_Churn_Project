# 📊 Customer Churn Prediction using Logistic Regression
<img width="1344" height="768" alt="IMG_20260212_085951" src="https://github.com/user-attachments/assets/9562dcf3-fe7a-45c8-89af-6b95cb54b2ae" />



## 📌 Project Overview

This project focuses on predicting customer churn using a **Logistic Regression** model.  
Customer churn prediction enables businesses to identify customers who are likely to leave and take proactive retention actions.

The project follows a complete end-to-end machine learning workflow including data exploration, preprocessing, model building, evaluation, and interpretation.

---

## 🎯 Problem Statement

The objective is to build a binary classification model that predicts whether a customer will churn (1) or not (0).

- **Target Variable:** `Churn`
- **Problem Type:** Binary Classification

---

## 📂 Dataset Description

The dataset includes customer-related information such as:

- Demographic details  
- Account information  
- Subscription type  
- Service usage  
- Billing and payment details  

### Feature Types:
- **Numerical Features:** e.g., tenure, monthly charges  
- **Categorical Features:** e.g., contract type, payment method  
- **Target Feature:** Churn (0/1)

---

## 🔎 Exploratory Data Analysis (EDA)

During the analysis phase:

- Checked data structure and feature types  
- Identified and handled missing values  
- Analyzed class distribution (churn imbalance)  
- Explored relationships between features and churn  

### Key Insights:

- Customers with shorter tenure are more likely to churn.
- Higher monthly charges slightly increase churn probability.
- Contract type significantly impacts churn behavior.
- Certain categorical features strongly influence churn risk.

---

## ⚙️ Data Preprocessing

### ✔ Encoding Categorical Variables
- Binary categorical features → Label Encoding  
- Multi-category features → One-Hot Encoding  

### ✔ Feature Scaling
- Applied **StandardScaler** to numerical features  
- Important because Logistic Regression is sensitive to feature scaling  

### ✔ Feature Importance (Selection)
- Risk Ratio

### ✔ Train-Test Split
- 80% Training  
- 20% Testing  

### 🛠️ Technologies Used

- **Python** – Core programming language used for model development  
- **Pandas** – Data manipulation and preprocessing  
- **NumPy** – Numerical computations and array operations  
- **Scikit-learn** – Machine learning modeling and evaluation  
- **Matplotlib & Seaborn** – Data visualization and exploratory analysis  
- **VS Code** – Development environment

---

## 🤖 Model Building

- Model used : **LogisticRegression**


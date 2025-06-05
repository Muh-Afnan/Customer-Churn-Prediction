# 📉 Customer Churn Prediction

A machine learning project designed to predict whether a customer is likely to churn (discontinue a service). This is a critical use case in customer retention strategies across industries such as telecommunications, banking, and SaaS platforms.

---

## 🧠 Problem Statement

Customer churn has a direct impact on business revenue. Identifying customers who are likely to churn allows companies to take proactive steps in improving satisfaction and reducing churn rates. This project aims to:

- Analyze customer behavior and service usage
- Build a predictive model for churn
- Improve business decision-making with actionable insights

---

## 🔍 Project Highlights

- ✅ Binary classification problem (Churn: Yes/No)
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data preprocessing and feature engineering
- 🧠 Machine Learning modeling (Logistic Regression, Random Forest, XGBoost)
- 📈 Performance evaluation (ROC AUC, Confusion Matrix, etc.)
- 💾 Trained model saving and optional deployment pipeline

---
## 🧠 Technologies Used

- Python
- TensorFlow
- NumPy, Pandas
- Matplotlib
- Jupyter Notebook

---

## 🗂️ Project Structure
customer-churn-prediction/
├── data/
│ └── customer_churn.csv # Dataset (or script to download)
├── notebook/
│ └── churn_prediction.ipynb # Main Jupyter notebook
├── src/
│ └── model.py # ML model functions (modularized)
├── saved_model/
│ └── churn_model.pkl # Trained model file (optional)
├── requirements.txt # List of dependencies
└── README.md # Project documentation

---

## 🧠 Model Architecture

- Flatten input: 28x28 → 784
- Dense(128), ReLU
- Dense(64), ReLU
- Dense(10), Softmax

---

## 📊 Results

<!-- - Train Accuracy: 99.5%
- Validation Accuracy: 97.8%
- Test Accuracy: 97.9% -->

---

## 📊 Dataset

**Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

**Description:**  
The dataset contains 7,043 customer records including demographics, account information, service details, and churn labels.

**Features Include:**
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `MonthlyCharges`, `TotalCharges`
- `PhoneService`, `InternetService`, `StreamingTV`
- `Contract`, `PaymentMethod`
- `Churn` (Target variable)

---

**⭐ Acknowledgements:**
- Kaggle Telco Dataset
- Scikit-learn Documentation
- XGBoost Docs
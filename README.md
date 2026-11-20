# 📡 Telecom Customer Churn Analysis & Prediction

### A Data Analytics and Machine Learning Project

An end-to-end Telecom Customer Churn Prediction project that combines **Python, Machine Learning, and Power BI** to analyse customer behaviour, identify churn patterns, and predict customers who are likely to leave a telecom service provider.

---

## 📌 Project Overview

Customer churn is one of the major challenges faced by telecom companies. Losing customers directly affects revenue and business growth.

This project aims to analyse customer data, understand the factors responsible for customer churn, and build a Machine Learning model to predict customers who are at risk of leaving the company.

The project also includes interactive Power BI dashboards to present business insights and customer retention opportunities.

## 🎯 Project Objectives

- Analyse customer behaviour and subscription patterns.
- Identify important factors responsible for customer churn.
- Perform data cleaning and preprocessing.
- Apply feature engineering techniques.
- Build and compare different Machine Learning models.
- Predict customer churn and churn probability.
- Categorize customers based on churn risk.
- Create interactive Power BI dashboards for business insights.

---

## 🛠️ Technologies & Tools Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |
| Business Intelligence | Microsoft Power BI |
| Data Storage | CSV, Excel |

---

## 📂 Project Structure

```text
Telecom-Customer-Churn-Prediction/
│
├── Dataset/
│   ├── dataset.csv
│   └── Cleaned.csv
│
├── Notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   └── 02_Feature_Engineering.ipynb
│
├── PowerBI/
│   ├── Churn_Analysis.pbix
│   └── Churn_Prediction.pbix
│
├── Results/
│   ├── model_comparison.csv
│   ├── final_model_evaluation.csv
│   ├── feature_importance.csv
│   ├── customer_churn_predictions.csv
│   └── customer_churn_predictions_full.csv
│
├── Images/
│   ├── churn_analysis.png
│   └── churn_prediction.png
│
├── Models/
│
├── requirements.txt
│
└── README.md
```

---

## 📊 Dataset Information

The dataset contains **7,043 customer records** and 21 columns.

It includes customer information, subscription details, services, billing information, and churn status.

### Important Features

| Feature | Description |
|---|---|
| customerID | Unique customer identifier |
| gender | Customer gender |
| SeniorCitizen | Senior citizen status |
| Partner | Whether customer has a partner |
| Dependents | Whether customer has dependents |
| tenure | Number of months with the company |
| InternetService | Internet service type |
| Contract | Contract type |
| PaymentMethod | Customer payment method |
| MonthlyCharges | Monthly customer charges |
| TotalCharges | Total customer charges |
| Churn | Whether the customer left the company |

**Target Variable:** `Churn`

- Yes – Customer has left the company.
- No – Customer has retained the service.

---

## 🔄 Project Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Model Training
8. Model Comparison
9. Model Evaluation
10. Customer Churn Prediction
11. Power BI Dashboard Development
12. Business Insights

---

## 🤖 Machine Learning Models

The following Machine Learning algorithms were compared:

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier

### 📈 Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 80.62% | 65.93% | 55.88% | 60.49% | 84.22% |
| Random Forest | 80.20% | 66.10% | 52.14% | 58.30% | 83.86% |
| Decision Tree | 79.42% | 63.12% | 54.01% | 58.21% | 82.67% |

### 🏆 Best Performing Model

**Logistic Regression**

- Accuracy: 80.62%
- Precision: 65.93%
- Recall: 55.88%
- F1 Score: 60.49%
- ROC-AUC: 84.22%

Logistic Regression achieved the highest accuracy, F1 score, and ROC-AUC among the three evaluated models.

---

## 📊 Power BI Dashboards

Two interactive dashboards were developed to analyse customer churn and prediction results.

### 1. Telecom Customer Churn Analysis Dashboard

This dashboard focuses on historical customer behaviour and business performance.

**Key Insights:**
- Total Customers: 7,043
- Churned Customers: 1,869
- Retained Customers: 5,174
- Average Monthly Charges: 64.76
- Total Charges: 16.06M

**Visualizations:**
- Customer Churn Distribution
- Churn by Contract Type
- Churn by Internet Service
- Churn by Payment Method
- Churn by Customer Tenure
- Revenue and Churn Analysis

### 2. Customer Churn Prediction Dashboard

This dashboard focuses on Machine Learning predictions and customer risk analysis.

**Key Features:**
- Predicted Retained Customers
- Predicted Churn Customers
- Risk Distribution
- Churn Probability by Contract
- Risk Analysis by Tenure
- Top 10 High-Risk Customers
- Customer Risk Categorization

---

## 💡 Key Business Insights

- Month-to-month contract customers show higher churn rates.
- Customers using electronic check payment methods have higher churn.
- Customers with shorter tenure are more likely to leave.
- Fiber optic internet customers contribute significantly to churn.
- Contract type, tenure, and monthly charges are important predictive features.
- Identifying high-risk customers can help businesses develop better retention strategies.

---

## 🚀 Future Improvements

- Develop a web application using Streamlit.
- Deploy the trained Machine Learning model.
- Build a real-time customer churn prediction system.
- Implement automated customer retention recommendations.
- Improve model recall to identify more potential churn customers.

---

## 👨‍💻 Author

**Shubham Pal**

MCA | AI & Data Science | Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Power BI | Machine Learning | Data Analytics

🔗 **GitHub:** https://github.com/Shubham05-tech

🔗 **Portfolio:** https://shubham05-tech.github.io/portfolio/

---

⭐ If you find this project useful, feel free to explore the repository and give it a star!

**Thank you for visiting!**

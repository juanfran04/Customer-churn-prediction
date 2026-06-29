# 📉 Customer Churn Prediction

End-to-end machine learning project for predicting customer churn using exploratory data analysis, feature engineering, and classification models.

---

## 📌 Project Overview

Customer churn is one of the main challenges faced by subscription-based businesses. Predicting which customers are likely to leave allows companies to design proactive retention strategies and reduce customer loss.

This project follows a complete data science workflow, from data cleaning and exploratory data analysis (EDA) to predictive modeling and business recommendations.

---

## 🎯 Objectives

- Explore customer behavior through data analysis.
- Identify the main factors associated with churn.
- Build and compare machine learning models.
- Generate business insights to support customer retention strategies.

---

## 📂 Dataset

The dataset contains information from **7,043 customers** of a telecommunications company, including:

- Customer demographics
- Contract information
- Services subscribed
- Billing information
- Customer tenure
- Churn status

**Target variable**

- **Churn Value**
  - 0 → Customer stayed
  - 1 → Customer churned

---

## 🔍 Exploratory Data Analysis

The exploratory analysis focused on:

- Distribution of categorical and numerical variables
- Correlation analysis
- Churn rate by customer characteristics
- Hypothesis testing

Some important findings include:

- Customers with month-to-month contracts have the highest churn rate.
- The first months of the customer lifecycle are the most critical.
- Additional services such as Online Security and Tech Support are associated with lower churn.
- Customers paying with Electronic Check tend to churn more frequently.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Removal of irrelevant and leakage variables
- One-Hot Encoding
- Train/Test Split (80/20)
- Feature Standardization (Logistic Regression)

---

## 🤖 Machine Learning Models

The following models were trained:

- Logistic Regression
- Random Forest

### Model Performance

| Model | Accuracy | Recall |
|--------|----------|---------|
| Logistic Regression | 80.2% | 57.2% |
| Random Forest | 79.6% | 51.1% |

Logistic Regression was selected as the final model because it achieved higher recall while remaining fully interpretable.

---

## 💡 Business Recommendations

Based on the analysis, several actions could help reduce customer churn:

- Focus retention efforts during the first months of the customer lifecycle.
- Encourage migration from month-to-month to long-term contracts.
- Promote value-added services such as Online Security and Tech Support.
- Monitor customers using Electronic Check.
- Develop personalized retention campaigns for customers without partners or dependents.

---

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure

```
customer-churn-prediction/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── customer_churn_prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

Possible future enhancements include:

- Hyperparameter tuning
- Cross-validation
- Gradient Boosting models (XGBoost, LightGBM)
- SHAP values for model explainability
- Deployment as a web application

---

## 👤 Author

**Juan Francisco Pereyra**

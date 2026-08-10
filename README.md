# Telecom Customer Churn Prediction & MLOps

An end-to-end Data Science and MLOps project focused on predicting customer churn in the telecommunications industry.

## 📌 Problem Statement

Customer churn is a major business problem for telecom companies.

Instead of waiting for customers to leave, the goal of this project is to identify customers who are likely to churn **before they actually leave**, understand the factors associated with churn, and support data-driven customer retention decisions.

The project will eventually combine:

**Data Science + Business Analytics + Machine Learning + MLOps**

---

## 📊 Current Progress

### 1. Data Understanding & Cleaning

Worked with the Telco Customer Churn dataset containing:

- 7,043 customer records
- 21 features
- Customer demographics
- Services subscribed
- Contract information
- Payment information
- Monthly and total charges
- Churn status

Data preparation included:

- Understanding dataset structure
- Checking data types
- Identifying missing values
- Handling `TotalCharges`
- Checking categorical variables
- Checking the target variable
- Preparing a cleaned dataset

---

### 2. Exploratory Data Analysis

Performed descriptive and diagnostic analysis to understand customer churn patterns.

Analyzed relationships between churn and:

- Contract type
- Internet service
- Customer tenure
- Monthly charges
- Payment method
- Technical support
- Online security
- Customer demographics

### Key finding

The overall churn rate in the dataset is approximately:

**26.58%**

Some observed patterns include:

- Month-to-month customers have substantially higher churn.
- Fiber-optic customers have a higher observed churn rate.
- Newer customers show higher churn rates.
- Higher monthly-charge groups show increased churn in the current analysis.

These findings represent relationships observed in the historical data and do not necessarily imply causation.

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to analyze customer churn.

### Current dashboard includes:

- Total Customers
- Churned Customers
- Overall Churn Rate
- Average Monthly Charges
- Churn by Contract
- Churn by Internet Service
- Churn Rate by Contract
- Churn Rate by Internet Service
- Churn Rate by Customer Tenure
- Churn Rate by Monthly Charges

Interactive filters allow users to explore different customer segments.

## 📊 Power BI Dashboard(Customer retention analysis)

An interactive Power BI dashboard was created to analyze customer churn patterns and provide business-oriented insights.

### Dashboard Preview

The complete dashboard is available here:

[📊 View Power BI Dashboard PDF](reports/telecom_churn_dashboard.pdf)
---

## 🤖 Machine Learning — Next Stage

The next stage of the project is to build a machine learning system that predicts whether a **new customer is likely to churn**.

Planned steps:

1. Feature engineering
2. Encoding categorical variables
3. Train/test split
4. Model training
5. Model comparison
6. Hyperparameter tuning
7. Model evaluation
8. Churn probability prediction

The model will eventually produce predictions such as:

```text
Customer A → 82% probability of churn
Customer B → 15% probability of churn
Customer C → 64% probability of churn
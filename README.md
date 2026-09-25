# Telco Customer Churn & Retention Intelligence

An end-to-end customer churn analysis and machine learning project using telecom customer data to understand churn patterns, predict customer churn risk, explain model predictions, and identify customers who may require retention attention.

## Project Overview

Customer churn is an important business problem for subscription-based companies. Understanding which customers are more likely to leave can help organizations identify at-risk customer segments and prioritize retention efforts.

In this project, I analyze customer-level telecom data using exploratory data analysis and machine learning. The project will combine:

- Exploratory Data Analysis (EDA)
- Customer churn prediction
- Logistic Regression
- XGBoost
- Model evaluation
- SHAP-based explainability
- Customer risk scoring
- Revenue-at-risk analysis
- Retention priority analysis
- Power BI dashboard

The project is inspired by research on explainable customer churn prediction using tabular machine learning models.

---

## Objectives

The main objectives of this project are:

1. Understand the major patterns associated with customer churn.
2. Identify customer segments with higher observed churn rates.
3. Build machine learning models to predict customer churn.
4. Compare a baseline Logistic Regression model with XGBoost.
5. Evaluate the models using multiple classification metrics.
6. Generate customer-level churn probabilities.
7. Segment customers into different churn-risk groups.
8. Use SHAP to understand which features influence model predictions.
9. Estimate simplified revenue-at-risk using churn probability and monthly charges.
10. Create a retention-priority framework for identifying high-risk and high-value customers.
11. Build a Power BI dashboard to communicate the analysis and business insights.

---

## Research Foundation

This project is inspired by the paper:

**Poudel, S., Pokharel, S., & Timilsina, M. (2024).  
"Explaining customer churn prediction in telecom industry using tabular machine learning models."  
Machine Learning with Applications, 17, 100567.**

The research emphasizes not only predicting customer churn but also explaining model predictions using SHAP.

This project adapts the general idea of combining churn prediction with explainability while adding a business-oriented risk prioritization layer.

---

## Dataset

The project uses the IBM Telco Customer Churn dataset.

The dataset contains customer-level information about:

- Demographics
- Account information
- Contract type
- Tenure
- Internet services
- Additional services
- Payment method
- Monthly charges
- Total charges
- Customer churn status

### Dataset dimensions

- **Rows:** 7,043 customers
- **Original columns:** 21
- **Target variable:** `Churn`

The target variable contains:

- `Yes` → customer churned
- `No` → customer did not churn

---

## Project Workflow

```text
Raw Customer Data
        ↓
Data Understanding
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Train/Test Split
        ↓
Logistic Regression
        ↓
XGBoost
        ↓
Model Evaluation
        ↓
Churn Probability
        ↓
Customer Risk Segmentation
        ↓
SHAP Explainability
        ↓
Revenue-at-Risk Analysis
        ↓
Retention Priority Analysis
        ↓
Power BI Dashboard
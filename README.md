# Customer Lifetime Value & Churn Prediction using Survival Analysis + Gradient Boosting

## Project Summary
Built an end-to-end **Customer Analytics system** to predict churn risk, estimate customer lifetime, and calculate Customer Lifetime Value (CLV). The goal was to identify **high-value customers at risk of churn** and enable targeted retention strategies.

This project combines **Gradient Boosting (XGBoost)** for churn prediction and **Survival Analysis (Cox Proportional Hazards)** to estimate time-to-churn.

---

## Business Problem
Customer churn directly impacts revenue. Companies need to know:

- Which customers are likely to churn?
- When are they likely to churn?
- Which customers are worth saving?
- Where should retention budget be spent?

This project answers all four.

---

## What I Built

### 1. Churn Prediction Model
- Model: XGBoost
- Predicts probability of customer churn
- Used for retention targeting

Outcome:
Identified high-risk customers with strong classification performance.

---

### 2. Survival Analysis Model
- Model: Cox Proportional Hazards
- Predicts time until customer churn
- Produces survival curves

Outcome:
Estimated customer lifetime and churn timing.

---

### 3. Customer Lifetime Value (CLV)
Calculated using:

CLV = Expected Lifetime × Monthly Revenue

Outcome:
Ranked customers by long-term revenue value.

---

## Dataset
IBM Telco Customer Churn dataset  
~7,000 telecom customers  

Features:
- Tenure
- Monthly charges
- Contract type
- Services
- Demographics
- Churn label

---

## Key Results

- Built churn prediction model with strong ROC-AUC performance
- Estimated survival probability for each customer
- Calculated CLV for customer ranking
- Identified high-value customers at churn risk
- Enabled targeted retention strategy

---

## Visualizations

### Feature Importance
Shows key drivers of churn prediction.

Insight:
Tenure and monthly charges are strong churn predictors.

Why it matters:
Helps business understand churn drivers.

---

### Survival Curve
Shows probability customers remain active over time.

Insight:
Steep drop indicates high churn risk period.

Why it matters:
Determines optimal retention timing.

---

### CLV Distribution
Shows spread of customer value.

Insight:
Small group contributes large revenue.

Why it matters:
Focus retention budget on high-value customers.

---

### Churn Probability Distribution
Shows model risk segmentation.

Insight:
Customers can be divided into high/medium/low risk.

Why it matters:
Automates retention targeting.

---

## Business Impact
This system enables:

- Proactive churn prevention
- Targeted retention campaigns
- Customer value segmentation
- Revenue risk forecasting
- Efficient retention budget allocation

Example use:
Retain top 10% highest CLV customers at risk of churn.

---

## Skills Demonstrated
Machine Learning  
Customer Analytics  
Survival Analysis  
Gradient Boosting (XGBoost)  
Feature Engineering  
CLV Modeling  
Business Impact Analysis  
Data Visualization  

---

## Project Outcome

Developed a production-style customer analytics pipeline that predicts churn, estimates lifetime value, and enables data-driven retention strategies.
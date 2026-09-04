# Telco Customer Churn Analysis

## Overview
This project analyzes customer churn patterns using the Telco Customer Churn dataset (7,043 customers) to identify the key factors driving customers to leave, and provides data-backed recommendations to reduce churn.

## Tools Used
- Python
- Pandas (data cleaning, GroupBy analysis)
- Matplotlib (data visualization)
- Google Colab

## Process
1. **Data Cleaning:** Converted `TotalCharges` to a numeric type, identified and removed 11 rows with missing values, and confirmed no duplicate records.
2. **Exploratory Data Analysis:** Calculated overall churn rate and analyzed churn patterns across contract type, internet service, payment method, and customer tenure using GroupBy aggregation.
3. **Visualization:** Built bar charts to compare churn rates across key categorical features.

## Key Findings & Recommendations
This analysis found an overall churn rate of 26.6%.

1. **Contract type is the strongest driver of churn.** Month-to-month customers had a churn rate of 42.7%, nearly 15 times higher than two-year contract customers (2.8%). The company should offer discounts or incentives to encourage month-to-month customers to switch to longer-term contracts.

2. **Fiber optic customers show higher dissatisfaction.** Their churn rate (41.9%) is more than double that of DSL customers (19%), which may point to pricing or service quality issues. The company should review Fiber optic pricing and gather customer feedback.

3. **Electronic check users churn at a much higher rate.** Customers paying via electronic check churned at 45.3%, roughly three times higher than those using automatic payment methods (15–17%). Offering incentives to switch to automatic payments could help reduce churn.

4. **Newer customers are at greater risk of leaving.** Churned customers had an average tenure of just 18 months, compared to 37.6 months for retained customers. The company should implement a targeted retention program for customers in their first year.

## Dataset
[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

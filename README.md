# Financial Risk Analysis with Python – Barclays

## Project Overview

This project focuses on analyzing real-world banking transaction data from Barclays to identify customer behavior patterns, financial risks, dormant accounts, anomalies, and balance stability. Python-based data analysis and statistical techniques are used to generate actionable insights for financial risk monitoring and customer management.

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* SciPy (Hypothesis Testing)
* Jupyter Notebook

---

## Dataset Description

* 800 transaction records
* 15 variables including customer, account, transaction, balance, and risk indicators
* Date range: January 2023 – June 2024

---

## Project Objectives

* Analyze customer transaction behavior and trends
* Identify dormant and low-activity accounts
* Detect overdrafts and negative balances
* Measure balance volatility and financial risk
* Detect anomalous transactions using IQR and Z-score
* Segment customers based on balance and transaction volume
* Perform hypothesis testing on transaction behavior

---

## Data Cleaning & Validation

* Verified numeric columns (no special characters or currency symbols)
* Handled negative values as valid overdrafts/refunds
* Confirmed zero null values
* Converted dates to datetime format
* Extracted year, month, day, and weekday features
* Standardized categorical columns

---

## Exploratory Data Analysis (EDA)

* Monthly and yearly transaction trends
* Credit vs debit behavior
* Net inflow and outflow analysis
* Customer activity and dormancy analysis

---

## Financial Risk Analysis

* Identified negative balance and overdraft accounts
* Calculated balance volatility using coefficient of variation (CV)
* Detected anomalies using IQR and Z-score methods
* Flagged high-risk and unstable accounts

---

## Customer Segmentation

* Segmented customers by:

  * Balance level (Low / Medium / High)
  * Transaction volume (Low / High)
* Identified high-balance but low-engagement customers

---

## Hypothesis Testing

* Tested whether high transaction volume leads to higher balances
* Result: No statistically significant relationship found

---

## Key Insights

* Customer activity declined significantly from 2023 to 2024
* High dormancy risk across multiple accounts
* Overdrafts and high-volatility accounts indicate financial stress
* Few accounts contribute most of the net inflows

---

## Business Recommendations

* Proactively engage dormant and low-activity customers
* Monitor overdraft and high-volatility accounts closely
* Run retention campaigns for high-balance, low-engagement customers
* Strengthen anomaly detection and risk alerts




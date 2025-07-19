# End-to-End Churn Analysis Project

This project focuses on identifying and predicting customer churn using an end-to-end data pipeline involving **SQL**, **Power BI**, and **Python (Machine Learning)**.

---

## 📌 Project Overview

- **Objective:** Analyze customer behavior and predict churn for a telecom company.
- **Tools Used:** SQL Server, Power BI, Python (Pandas, sklearn, matplotlib)

---

## 🧩 Project Steps

### 1. Data Cleaning & Transformation (SQL)
- Removed nulls, duplicates, and standardized fields.
- Created calculated columns like tenure groups and churn flags.
- Loaded cleaned data into SQL tables.

### 2. Dashboarding (Power BI)
- Built interactive dashboard to track:
  - Total Customers
  - Churned Customers
  - Churn Rate (%)
  - Customer Segments by Region, Contract, and Services
- Added filters, slicers, and dynamic visuals.

### 3. Machine Learning Model (Python)
- Used Random Forest Classifier to predict churn.
- Processed features with Label Encoding and train-test split.
- Evaluated with accuracy score, confusion matrix, and classification report.

---

## 📊 Key Outcomes

- Built a **fully functional dashboard** with actionable KPIs.
- Achieved **~85% model accuracy** in predicting customer churn.
- Identified top churn indicators like contract type, monthly charges, and service usage.

---

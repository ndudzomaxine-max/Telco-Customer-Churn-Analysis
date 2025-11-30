# 📊 Telco Customer Churn Analysis
### *Excel • SQL • Power BI • End-to-End Data Analytics Project*

This project provides a complete analysis of customer churn using the Telco dataset.  
The goal is to uncover factors influencing churn by performing data cleaning, SQL analysis, and creating a Power BI dashboard.

---

## ✅ Project Overview
The Telco Customer Churn dataset contains information about telecom customers including demographics, account details, service types, and churn status.

This end-to-end project includes:

### ✔ Excel — Data Cleaning & Feature Engineering
- Removed duplicates and blanks  
- Standardized text fields  
- Converted Yes/No values to binary flags  
- Created new engineered fields:
  - `Churn Flag (0/1)`
  - `Tenure Band`
  - `SeniorCitizen Flag (0/1)`
  - `Partner Flag (0/1)`
- Saved final cleaned dataset as: **`telco_clean.xlsx`**

---

## ✔ SQL — Insights & Business Queries
Executed SQL queries using SQLite Studio to answer key business questions.

### SQL insights included:
- Total customers  
- Total churned customers  
- Churn rate  
- Churn by gender  
- Churn by contract type  
- Churn by tenure band  
- Churn by payment method  
- Average monthly charges  

All SQL queries saved as: **`telco_churn_sql_queries.txt`**

---

## ✔ Power BI — Interactive Dashboard
A professional dashboard was built to visualize churn patterns.

### Key KPIs
- **Total Customers:** 7,043  
- **Total Churn Count:** 1,869  
- **Churn Rate:** 26.54%  
- **Average Monthly Charge:** \$64.76  

### Visuals Included
- Churn by Contract Type  
- Churn by Tenure Band  
- Churn by Internet Service  
- Churn by Payment Method  
- Churn by Senior Citizen  
- Churn by Gender  
- Churn by Churn Reason (if included)

Dashboard exported as: **`Telco_Churn_Dashboard.pdf`**

---

## 🗂 Repository Contents

| File | Purpose |
|------|---------|
| `telco_clean.xlsx` | Final cleaned dataset |
| `telco_churn_sql_queries.txt` | All SQL queries used |
| `Telco_Churn_Dashboard.pdf` | Final Power BI dashboard |
| `README.md` | Documentation |

---

## 🧠 Key Insights & Conclusions
- Customers on **month-to-month contracts** are most likely to churn.  
- Users paying via **electronic check** have the highest churn rate.  
- **Fiber optic** customers churn more due to price and service quality issues.  
- Customers with **5+ years tenure** churn significantly less.  
- Senior citizens and customers with no dependents show higher churn.

These insights can help telecom providers optimize their retention strategies.

---

## 🚀 Tools Used
- **Microsoft Excel** — Cleaning & feature engineering  
- **SQLite / SQL** — Querying & insight generation  
- **Power BI** — Dashboard creation  
- **GitHub** — Version control & project showcase  

---

## 👩🏽‍💻 Author
**Tsitsi Maxine Ndudzo**  
Data Analyst (Excel • SQL • Power BI • Python)

---


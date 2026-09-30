# Customer Churn Analysis

## 📊 Project Overview

Customer churn is an important business problem because customer cancellations can directly affect revenue and customer retention.

This project analyzes customer churn data to identify churn patterns, customer behavior, subscription trends, revenue at risk, complaints, escalations, and churn-risk segments.

The project follows an end-to-end data analytics workflow using Python, SQLite, Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Calculate the overall customer churn rate
- Calculate the customer retention rate
- Analyze churn by plan type
- Analyze churn by state
- Analyze churn by subscription type
- Calculate customer age
- Calculate average customer tenure
- Calculate ARPU (Average Revenue Per User)
- Identify revenue at risk
- Analyze customer complaints
- Analyze support escalations
- Examine the relationship between escalations and churn
- Categorize customers based on churn risk
- Create visualizations to communicate business insights

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation |
| NumPy | Numerical calculations and feature engineering |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| SQLite | Database storage and querying |
| Jupyter Notebook | Development and analysis |
| Excel | Source data |

---

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── README.md
├── notebooks/
│   └── Churn_Analysis.ipynb
│
├── data/
│   └── customer_churn_data_raw.xlsx
│
├── database/
│   └── customer_churn.db
│
├── images/
│   ├── database_tables.png
│   ├── kpi_table.png
│   ├── churn_definition.png
│   ├── churn_by_plan.png
│   ├── churn_by_state.png
│   ├── churn_by_subscription.png
│   └── correlation_heatmap.png
│
├── reports/
│   └── Churn_Analysis.pdf
│
└── requirements.txt
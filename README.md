# 🎯 Customer Churn Intelligence System

An end-to-end churn analytics solution combining **SQL Server**, **Power BI**, and **Machine Learning (Random Forest in Python)** to proactively predict customer churn and surface strategic insights through dynamic dashboards.

> 🧠 “Reducing churn is not just a data challenge — it's a business growth strategy.”  
> This project goes beyond prediction by blending **data engineering**, **ML**, and **business intelligence** to influence decision-making at scale.

---

## 📌 Problem Statement

High churn leads to direct revenue loss and increased customer acquisition costs.  
The business challenge:  
**“Which customers are likely to leave and why?”**

---

## 🧭 Project Objectives

- 🧼 Clean and model customer data from SQL Server.
- 📊 Design KPIs and metrics using Power BI.
- 🧠 Build a machine learning model to predict churners.
- 📈 Deliver interactive dashboards with actionable business insights.
- 🧩 Recommend churn-reduction strategies for high-risk segments.

---

## 🧠 Solution Architecture

```plaintext
                ┌──────────────┐
                │   Raw Data   │
                └────┬─────────┘
                     ▼
        ┌──────────────────────────┐
        │ SQL Server (ETL Layer)   │
        │ - Joins & Cleanup        │
        │ - Feature Engineering    │
        └────────────┬─────────────┘
                     ▼
        ┌──────────────────────────┐
        │ Power BI (BI Layer)      │
        │ - KPIs & Visual Models   │
        │ - Churn Heatmaps         │
        └────────────┬─────────────┘
                     ▼
        ┌──────────────────────────┐
        │ Python (ML Layer)        │
        │ - Random Forest Classifier│
        │ - Churn Prediction Scores │
        └──────────────────────────┘

  🧪 Machine Learning Details

  Model Used: Random Forest Classifier  
  Accuracy Achieved: 84%

 Metrics
- 🎯 Precision: 78%
- 🔁 Recall: 65%

  Top Features Identified
- Contract Type
- Monthly Charges
- Tenure
- Total Charges
- Internet Type

  📊 Power BI Dashboards

  1️⃣ Churn Overview Dashboard
  Visuals:
- Churn by gender, contract type, tenure, state, and age group

  KPIs
- Churn Rate
- Average Charges
- Retention Ratio

  2️⃣ ML-Driven Churn Prediction Dashboard
  Visuals:
- Predicted churn probabilities from Python model

  Filters:
- Contract Type
- Region
- Customer Type
- High-Risk Flags

  Integration:
- CSV predictions generated by Python imported into Power BI


  🔍 Key Insights

- 📉 Month-to-month contract holders are significantly more likely to churn
- 💸 High monthly charges correlate with greater churn probability
- 🌐 Fiber Optic internet users churn more than DSL users
- ⏳ Most churn occurs within the first 6 months of customer tenure


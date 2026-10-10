# 📊 Churn Analysis and Customer Intelligence

## 📌 Overview
This project focuses on **churn analysis** in the OTT subscription industry (Netflix, Hotstar, Prime).  
It integrates **SQL and Python** to analyze customer demographics, subscription tiers, and support escalations, identifying high-risk subscribers and quantifying revenue impact.  


## 🎯 Business Challenge
In the hyper-competitive OTT landscape, **retention is critical**.  
The goal is to identify:
- **Who** is likely to churn  
- **Why** they churn (behavioral drivers)  
- **When** they enter the danger zone  

---

## 🛠️ Tech Stack
- SQL (sqlite3)  
- Python (numpy, pandas)  
- Visualization (matplotlib, seaborn)  
- Feature Engineering & Analytics  

---

## 📂 Project Roadmap
1. **Data Extraction** – Connect SQL database to Python  
2. **Data Cleaning** – Handle missing values, rename columns, QC checks  
3. **Feature Engineering** – Tenure, churn scores, escalations, ARPU  
4. **Exploratory Data Analysis (EDA)** – Aggregations, group-by, pivot tables  
5. **Visualization** – Churn by plan type, state, tenure, escalations  
6. **Insights & Reporting** – Translate findings into actionable business strategies  

---

## 📊 Key Metrics
- **Churn Rate** = churned customers / total customers  
- **Retention Rate** = 1 – churn rate  
- **ARPU** = SUM(monthly_charges) / COUNT(active customers)  
- **Revenue at Risk** = SUM(monthly_charges) WHERE churn_score > 70  
- **Escalation Rate** = SUM(escalations) / COUNT(complaints) × 100  

---

## 🔎 Insights
- Overall churn rate: **28.6%**  
- Retention rate: **71.4%**  
- Monthly contracts churned at **55.6%**, vs annual contracts at **8.3%**  
- Karnataka showed the highest churn spike in Sep 2024  
- Revenue loss due to churn: **18%** (~₹74)  
- CLTV lost: **₹2,047**  

---

## 🚀 Action Items
- Investigate churn spike in Karnataka (pricing, complaints, competitor activity).  
- Focus retention efforts on **high-risk cohorts** with high CLTV.  
- Prioritize **Premium annual-plan retention** over Basic monthly acquisition.  
- Address escalated support complaints to reduce churn correlation.  



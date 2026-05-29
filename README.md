# 🛍️ Retail customer Behavior Analysis
> End-to-end data analytics project simulating real-world retail business intelligence — from raw data to executive dashboard.

---

## 📊 Project Summary

| Detail | Info |
|--------|------|
| **Domain** | Retail / Consumer Behavior |
| **Dataset** | 3,900 transactions, 18 attributes |
| **Tools Used** | Python, SQL, PostgreSQL, Power BI |
| **Deliverables** | Cleaned Dataset, SQL Queries, Power BI Dashboard, Business Report |

---

## 🎯 Business Problem

A leading retail company needed to understand **why customers buy, when they buy, and who buys the most.**

> *"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"*

This project answers that question end-to-end — from messy raw data to actionable business recommendations.

---

## 🔄 Project Workflow

```
Raw Dataset → Python Cleaning → PostgreSQL Analysis → Power BI Dashboard → Business Report
```

---

## 🐍 Phase 1 — Data Preparation (Python)

- Imported 3,900 records with 18 columns using **Pandas**
- Resolved **37 missing values** in Review Rating using category-level median imputation
- Standardized all column names to snake_case for consistency
- Engineered **2 new features**: `age_group` and `purchase_frequency_days`
- Dropped redundant column `promo_code_used` after consistency check
- Connected Python script to **PostgreSQL** and loaded clean data for SQL analysis

---

## 🗄️ Phase 2 — Data Analysis (SQL)

Wrote **10 business-focused SQL queries** in PostgreSQL to answer key questions:

| # | Query | Insight |
|---|-------|---------|
| 1 | Revenue by Gender | Male: $157,890 vs Female: $75,191 |
| 2 | High-Spending Discount Users | 839 customers spent above average even with discounts |
| 3 | Top 5 Products by Rating | Gloves (3.86), Sandals (3.84), Boots (3.82) |
| 4 | Shipping Type Comparison | Express ($60.48) vs Standard ($58.46) avg spend |
| 5 | Subscribers vs Non-Subscribers | 1,053 subscribers vs 2,847 non-subscribers |
| 6 | Discount-Dependent Products | Hat (50%), Sneakers (49.66%), Coat (49.07%) |
| 7 | Customer Segmentation | 3,116 Loyal, 701 Returning, 83 New |
| 8 | Top 3 Products per Category | Jewelry, Blouse, Sandals lead their categories |
| 9 | Repeat Buyers & Subscriptions | 958 repeat buyers are subscribed |
| 10 | Revenue by Age Group | Young Adults lead at $62,143 |

---

## 📈 Phase 3 — Power BI Dashboard

Built an **interactive dashboard** with 6 visuals including:
- KPI cards: 3.9K customers, $59.76 avg purchase, 3.75 avg rating
- Revenue by Category and Age Group
- Subscription status breakdown (27% Yes / 73% No)
- Sales by Category with dynamic filters for Gender, Category, Shipping Type

---

## 💡 Business Recommendations

- **Boost Subscriptions** — Only 27% are subscribers; exclusive perks can convert the 73%
- **Target Young Adults** — Highest revenue group at $62,143; prioritize in campaigns
- **Review Discount Policy** — Products like Hat and Sneakers are over-discount-dependent
- **Loyalty Rewards** — 3,116 loyal customers identified; reward them to retain revenue
- **Express Shipping Promotion** — Express users spend more; highlight in marketing

---

## 📁 Repository Structure

```
📦 customer-shopping-behavior-analysis
├── 📂 data/
│   └── raw_dataset.csv
├── 📂 python/
│   └── data_cleaning.py
├── 📂 sql/
│   └── business_queries.sql
├── 📂 powerbi/
│   └── customer_behavior_dashboard.pbix
├── 📂 report/
│   └── retail_customer_insights_report.pdf
└── README.md
```

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 👤 Author

**Kazama** — Aspiring Data Analyst
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](www.linkedin.com/in/samrat-ashok-data-engineer)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/SamratashokAK)

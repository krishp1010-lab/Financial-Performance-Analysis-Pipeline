# 📊 Financial Performance Analysis & Strategic Spending Audit (2022–2023)

## 📌 Project Overview
This repository contains an end-to-end data analytics pipeline designed to unify fragmented company financial data and audit corporate spending performance. By connecting 5 disconnected operational tracking sheets (Budget, Customers, Transactions, Headcount, and Vendors), this pipeline exposes critical cost leakages, identifies systematic budget variances, and calculates key macro profitability metrics.

### 💰 Key Financial Highlights
* **Total Revenue Managed:** $864.61 Million
* **Net Take-Home Profit:** $696.87 Million
* **Profit Efficiency:** 80.60% Net Profit Margin
* **The Core Hurdle:** 60.88% Systemic Budget Overrun across all business units

---

## ⚙️ Technical Architecture & Pipeline Steps

### 1. Data Cleaning & Engineering (Python)
* Automated data ingestion and cleanup using `pandas` and `numpy`.
* Resolved a critical chronological date-parsing issue (`dayfirst=True`) across transaction sheets to eliminate timeline trend distortions.
* Connected and integrated relational data across tables using structured ID tracking keys.

### 2. Statistical Analysis & Testing
* Deployed ANOVA and t-testing to mathematically prove that the company's budget overruns were systemic failures rather than random flukes.
* Isolated **April 2023** as an extreme spending anomaly month for deep root-cause diagnostics.

### 3. Business Intelligence Modeling (Power BI)
* Engineered a star-schema relational data model with bidirectional filtering.
* Structured optimized calculations using custom DAX formulas (`Total Revenue`, `Total Expense`, `Budget Variance %`) to ensure rapid file performance.
* Developed a 2-page executive dark-theme dashboard separating macro vitals from micro operational deep-dives.

---

## 💡 Strategic Business Recommendations
1. **Procurement Consolidation:** Negotiate a mandatory 10% volume discount with our top 5 multi-purpose "convenience vendors" to return **~$5.6M annually** to net profit.
2. **Budget Re-Baselining:** Overhaul legacy budget targets to align with the hyper-growth of the Online channel.
3. **Resource Reallocation:** Shift 5% of underperforming physical regional assets directly into scalable Online Subscription models.

---

## 📂 Repository Contents
* `Financial_Performance_Analysis.ipynb`: Complete Python data cleaning, exploration, and statistical script.
* `Financial Performance analysis (Capstone project).pdf`: Clean executive-ready presentation deck.
* `README.md`: Project summary documentation.

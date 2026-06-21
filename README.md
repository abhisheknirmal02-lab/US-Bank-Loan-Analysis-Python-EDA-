# 🏦 Bank Loan Analysis — Power BI Report

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoft&logoColor=white)

An end-to-end analysis of a bank's loan portfolio — built to track lending performance, monitor repayment health, and segment risk across **38,576 loan applications** worth **$435.76M** in funded amount. The project combines Python-based exploratory data analysis with an interactive Power BI dashboard for business-facing reporting.

---

## 📌 Project Overview

Banks need to answer two questions continuously: *how much are we lending, and how much of it is coming back?* This project addresses that by building a portfolio-level view of loan applications, funded amounts, repayments, and risk classification (Good Loan vs. Bad Loan), with month-to-date (MTD) tracking for ongoing monitoring.

**Dataset:** 38,576 records × 24 fields — loan amount, interest rate, term, issue date, loan status, purpose, employment length, home ownership, state, DTI, and total payment received.

---

## 📊 Key KPIs

| Metric | Value |
|---|---|
| Total Loan Applications | 38,576 |
| MTD Loan Applications (Dec 2021) | 4,314 |
| Total Funded Amount | $435.76M |
| MTD Total Funded Amount | $53.98M |
| Total Amount Received | $473.07M |
| MTD Total Amount Received | $58.07M |
| Average Interest Rate | 12.05% |
| Average Debt-to-Income Ratio (DTI) | 13.33% |

### Loan Quality Breakdown

| Segment | Applications | % of Total | Funded Amount | Amount Received |
|---|---|---|---|---|
| ✅ Good Loan (Fully Paid + Current) | 33,243 | 86.18% | $370.22M | $435.79M |
| ❌ Bad Loan (Charged Off) | 5,333 | 13.82% | $65.53M | $37.28M |

---

## 🔍 Analysis Breakdown

- **Monthly Trends** — Funded amount, amount received, and application volume tracked month-over-month to spot seasonality and growth patterns
- **Regional Analysis** — Total funded amount by state, identifying top-lending geographies
- **Loan Term Analysis** — Funded amount split by loan term (36 vs. 60 months)
- **Employment Length** — Funded amount by borrower employment tenure
- **Loan Purpose** — Funded amount broken down by stated purpose (debt consolidation, credit card, home improvement, etc.)
- **Home Ownership** — Funded amount segmented by rent/own/mortgage status, visualized as a treemap

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python** (Pandas, NumPy) | Data cleaning, KPI calculation, MTD logic |
| **Matplotlib / Seaborn / Plotly** | Exploratory visualizations (trend lines, bar charts, treemap) |
| **Power BI** | Interactive dashboard with DAX measures for business reporting |
| **DAX** | KPI cards, Good/Bad loan measures, time-intelligence (MTD) calculations |

---

## 📁 Repository Structure

```
├── Bank_Loan_Analysis.ipynb     # Python EDA: KPIs, trends, segment analysis
├── financial_loan.csv           # Source dataset
├── Bank Loan Report.pbix        # Power BI dashboard
└── README.md
```

---

## 📷 Dashboard Preview

*(Add Power BI dashboard screenshots here)*

---

## 🚀 Key Insight

With an 86.18% good-loan rate but bad loans recovering only ~57% of their funded amount ($37.28M received against $65.53M funded), the analysis highlights where portfolio risk is concentrated — useful for refining underwriting criteria and prioritizing collections by term, purpose, and borrower profile.

---

## 🔗 Connect

Feel free to explore the dashboard and reach out if you'd like to discuss the approach or dataset.

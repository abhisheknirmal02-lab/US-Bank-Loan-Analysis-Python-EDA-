# 🏦 Bank Loan Analysis — Python EDA

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-nirmal-3b6325370/)

An end-to-end analysis of a bank's loan portfolio — built to track lending performance, monitor repayment health, and segment risk across **38,576 loan applications** worth **$435.76M** in funded amount. The project covers data cleaning, KPI calculation, and exploratory visualization entirely in Python.

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
| **Matplotlib / Seaborn** | Trend lines, bar charts, comparison visuals |
| **Plotly** | Interactive treemap (home ownership breakdown) |
| **Jupyter Notebook** | End-to-end analysis environment |

---

## 📁 Repository Structure

```
├── Bank Loan Analysis.ipynb     # Python EDA: KPIs, trends, segment analysis
├── financial_loan.csv           # Source dataset
├── dashboard_preview.png        # Composite chart overview
└── README.md
```

**Quick links:**
- 📓 [Bank Loan Analysis.ipynb](https://github.com/abhisheknirmal02-lab/US-Bank-Loan-Analysis-Python-EDA-/blob/main/Bank%20Loan%20Analysis.ipynb) — full notebook with code and outputs
- 📄 [financial_loan.csv](https://github.com/abhisheknirmal02-lab/US-Bank-Loan-Analysis-Python-EDA-/blob/main/financial_loan.csv) — source dataset

---

## 📷 Analysis Overview

![Dashboard Preview](https://github.com/abhisheknirmal02-lab/US-Bank-Loan-Analysis-Python-EDA-/blob/main/dashboard_preview.png?raw=true)

*All charts generated in Python (Matplotlib, Seaborn, Plotly) — composited here for a single-page overview. Full code and individual outputs are in the notebook.*

---

## 🚀 Key Insight

With an 86.18% good-loan rate but bad loans recovering only ~57% of their funded amount ($37.28M received against $65.53M funded), the analysis highlights where portfolio risk is concentrated — useful for refining underwriting criteria and prioritizing collections by term, purpose, and borrower profile.

---

## 🔗 Connect

Feel free to explore the notebook and reach out if you'd like to discuss the approach or dataset.

📌 [Connect with me on LinkedIn](https://www.linkedin.com/in/abhishek-nirmal-3b6325370/)

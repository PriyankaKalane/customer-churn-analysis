# 📉 Customer Churn Analysis — Telecom

An end-to-end data analytics project analyzing customer churn behavior in a telecom company using Python (EDA) and Power BI (interactive dashboard).

---

## Problem Statement

Customer churn is one of the biggest challenges in the telecom industry. This project analyzes 7,032 customer records to identify the key factors driving churn, helping business teams design targeted retention strategies.

---

## Key Findings

| Insight | Detail |
|---|---|
| Overall Churn Rate | 26.58% (1,869 out of 7,032 customers) |
| Retention Rate | 73.42% |
| Highest Risk Group | Month-to-month contract customers — 42.7% churn rate |
| Lowest Risk Group | Two-year contract customers — only 2.8% churn rate |
| Payment Method Risk | Electronic check users churn significantly more than automatic payment users |
| Internet Service | Fiber optic customers show higher churn than DSL customers |
| Avg Monthly Charges | Churned customers pay ₹74.44 vs ₹61.31 for retained customers |
| Tenure Pattern | Churned customers have average tenure of 18 months vs 38 months for retained |

---

## Dashboard Preview

![Customer Churn Dashboard](dashboard.png)

---

## Project Structure

```
customer-churn-analysis/
│
├── Churn_Project__1_.ipynb        # Python EDA notebook
├── customer_churn_dashboard.pbix  # Power BI interactive dashboard
├── dashboard.png                  # Dashboard screenshot
└── README.md                      # Project documentation
```

---

## Tools & Technologies

| Tool | Usage |
|---|---|
| Python | Data cleaning, EDA, visualizations |
| Pandas & NumPy | Data manipulation and analysis |
| Matplotlib & Seaborn | Charts and visual exploration |
| Power BI | Interactive business dashboard |
| GitHub | Version control |

---

## Methodology

1. **Data Loading** — Imported 7,032 telecom customer records (21 features)
2. **Data Cleaning** — Converted TotalCharges to numeric, handled 11 missing values, removed duplicates
3. **EDA** — Analyzed churn patterns by contract type, payment method, internet service, tenure, and charges
4. **Dashboard** — Built a 2-page interactive Power BI report with slicers for contract type and internet service

---

## Business Recommendations

Based on the analysis:
- **Target month-to-month customers** with incentives to upgrade to annual contracts — this alone could reduce churn from 42.7% to under 11%
- **Investigate fiber optic service quality** — disproportionately high churn suggests pricing or service issues
- **Encourage auto-pay adoption** — electronic check users churn at nearly 3x the rate of automatic payment users

---

## About

Built as part of a Post Graduate Program in Data Science & Analytics at Imarticus Learning, Pune.

**Author:** Priyanka Kalane
**LinkedIn:** [linkedin.com/in/priyankakalane](https://linkedin.com/in/priyankakalane)

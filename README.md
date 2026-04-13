# Customer-Analytics-Revenue-Audit
Predictive churn modeling and revenue expansion forecasting using Python, SQL, and Machine Learning.

# Customer Health & Revenue Expansion Audit

## Project Overview
In this project, I transitioned from a Customer Success mindset to a Data Analytics approach to solve two critical B2B SaaS challenges:
1. **Churn Mitigation:** Predicting which high-value accounts are likely to cancel.
2. **Revenue Forecasting:** Identifying "Value Gaps" where accounts are under-monetized based on their industry and usage.

## The Tech Stack
* **Python:** Pandas for data cleaning, Scikit-Learn for Machine Learning.
* **SQL:** Relational data joining and feature engineering.
* **Excel:** Professional dashboarding using Conditional Formatting and Icon Sets.
* **Models:** Random Forest (Classification) and Linear Regression (Forecasting).

---

## Phase 1: Churn Prevention (The Defensive Play)
I built a **Random Forest Classifier** to assign a "Risk Score" to every customer.
* **The Insight:** Identified that engagement frequency and contract type were the strongest predictors of retention.
* **The Result:** Produced a prioritized "At-Risk" list for the CS team, flagging accounts that represent a significant portion of Monthly Recurring Revenue (MRR).

## Phase 2: Revenue Expansion (The Offensive Play)
Using **Linear Regression**, I forecasted the "Ideal Revenue" for each account by comparing their current spend against industry benchmarks and usage intensity.
* **The "Value Gap":** Identified 1,800+ accounts with a high "Upsell Opportunity."
* **The Win:** Flagged specific Enterprise-tier accounts currently paying $0 who are prime candidates for immediate sales outreach.

---

## Dashboard Preview
*Note: GitHub previews strip away Excel formatting. Please see the screenshots below for the intended Business Dashboard view:*

### The "Upsell Hit List"
![Upsell Dashboard](YOUR_SCREENSHOT_NAME_HERE.png)
> **Visual Logic:** Gold stars indicate high-potential Enterprise accounts. The green heat map highlights the "Upsell Opportunity" dollar amount, allowing Sales teams to sort by the biggest potential wins.

---

## Repository Contents
* **`Revenue_Operations_Audit.ipynb`**: The full Python source code and diagnostic checks.
* **`High_Priority_Upsell_Opportunities.xlsx`**: The final actionable report for the Sales team (Download to view formatting).
* **`Retention_Risk_Analysis.xlsx`**: The prioritized churn list for the Customer Success team.

## Data Source
The analysis was performed on a B2B SaaS billing and usage dataset sourced from Kaggle. 
*Note: To maintain data privacy and repository efficiency, the raw CSV dataset is not hosted in this public repository.*

# 🚀 Credit Risk Early Warning System (Banking / FinTech)
---
<img width="913" height="618" alt="image" src="https://github.com/user-attachments/assets/e8793e6b-69b3-45cb-a8d7-e9eac0b6353c" />
---

Live App: https://credit-risk-early-warning-6vfwzmlz3pmxyjxrbxyxxm.streamlit.app/

---
## Business Objective
Detect early default risk before customers miss payments, enabling proactive intervention and loss prevention.

## Why This Matters

Defaults are expensive

Late intervention increases charge-offs

Early signals exist months before default

This system transforms raw transaction data into actionable risk intelligence.

## End-to-End Architecture
Raw Data → Feature Engineering → Risk Model → 
Threshold Optimization → Risk Tiers → 
Governance Monitoring → Executive Dashboard → Live App

## Business Outcome

The model identifies high-risk customers before missed payments, allowing financial institutions to implement early intervention strategies and reduce potential credit losses.

## Modeling Highlights

Gradient Boosting Classifier (Best ROC-AUC: 0.776)

Cost-sensitive threshold optimization

Risk tier segmentation (Low / Medium / High)

Feature explainability (delinquency & volatility driven)

Risk Governance

ROC stability monitoring

KS drift detection

PSI population stability tracking

Business threshold calibration

## Tools & Stack

Python (pandas, sklearn, matplotlib)

Streamlit (live risk scoring)

Power BI (executive monitoring)

Excel (advanced dashboarding)

GitHub (production structure)

## Live Demo

👉 Streamlit App: https://credit-risk-early-warning-6vfwzmlz3pmxyjxrbxyxxm.streamlit.app/

## Structure
```
credit-risk-early-warning-system
│
├── app
│   ├── gb_bundle (1).pkl
│   ├── requirements.txt
│   └── streamlit_app_—_credit_risk_early_warning_system.py
│
├── dashboards
│   └── Credit_Card_Dashboard.pbix
│
├── data
│   └── raw
│       └── default of credit card clients.xls
│
├── models
│   └── gb_bundle (1).pkl
│
├── notebooks
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_Modeling.ipynb
│   ├── 06_credit_risk_modeling_—_model_comparison.ipynb
│   ├── 07_model_calibration_business_cutoffs.ipynb
│   ├── 08_cost_sensitive_decision_analysis.ipynb
│   └── 09_model_goverance_&_monitoring.ipynb
│
└── README.md
```
Disclaimer

This project uses public data and is for educational demonstration only

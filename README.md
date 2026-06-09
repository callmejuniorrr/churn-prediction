# Telco Customer Churn Prediction

Machine learning project predicting customer churn for a telecom company,
with business recommendations and estimated revenue impact.

Live analysis : see `churn_analysis.ipynb`

---

## Project Overview

This project builds a churn prediction model on the IBM Telco dataset (7,043 customers).
Beyond the technical model, it delivers actionable business recommendations
with revenue-at-risk quantification and ROI estimation for retention campaigns.

---

## Results

| Metric | Value |
|--------|-------|
| Best Model | Logistic Regression |
| AUC-ROC | 0.842 |
| Recall (Churn) | 79% |
| Accuracy | 74% |

Logistic Regression outperformed XGBoost (AUC 0.842 vs 0.826),
demonstrating that simpler models can outperform complex ones
on linearly separable data.

---

## Key Business Findings

| Segment | Customers | Monthly Revenue at Risk |
|---------|-----------|------------------------|
| High Risk (>70%) | 374 | $29,771.95 |
| Medium Risk (40-70%) | 322 | $21,570.35 |
| Low Risk (<40%) | 713 | — |

**Total monthly revenue at risk : $51,342.30**
**Estimated annual impact : $616,107.60**
---

## Business Recommendations

1. **Strengthen onboarding** — dedicated customer success for first 3 months
2. **Push annual contracts** — 15-20% discount to reduce month-to-month churn
3. **Investigate fiber optic quality** — satisfaction survey + network audit
4. **Review pricing strategy** — introduce mid-tier plans, loyalty discounts after 6 months

Assuming a 30% success rate on high-risk customers, the model-driven
retention campaign is estimated to save $XX,XXX in annual revenue.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189E3C?style=flat)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-blue?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Project Structure

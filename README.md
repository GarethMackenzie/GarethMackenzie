<div align="center">

# Gareth Andrew Mackenzie

**Insurance Analytics · Data & BI · Fraud Detection · Process Optimization**

Johannesburg, South Africa

[![Email](https://img.shields.io/badge/Email-gamackenzie%40live.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gamackenzie@live.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gareth-andrew-mackenzie-50407b52/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GarethMackenzie)

</div>

---

Insurance operations professional applying data analytics to claims, fraud triage, business intelligence, and process improvement.

## About

I work at the intersection of insurance operations and data analytics — with claims and policy-administration experience since 2018, paired with hands-on Python, SQL, Power BI, and machine-learning work focused on fraud detection and operational improvement.

My strongest differentiator is domain context: I understand the business process behind claims data, the operational consequences of analytical decisions, and the importance of separating model performance from real-world business outcomes.

## Professional Impact
*Outcomes from day-to-day claims operations work — separate from the synthetic portfolio project below.*

| Metric | Result |
|---|---|
| Claims handling time | 40% faster after a redesign I led |
| Fraud identified / prevented | R500,000+ |
| Monthly claims volume managed | ~200 motor & agricultural claims |

## Flagship Project — Motor Claims Fraud Triage
*A portfolio case study built entirely on synthetic data. It is not a production system and is not connected to any employer's live claims data.*

**The problem.** Insurance fraud erodes loss ratios, but flagging too aggressively creates delays for legitimate policyholders. The project tests whether a limited review team can use model scores to concentrate attention on the claims most worth a second look.

**The approach.** Synthetic claims are generated in code, categorical features are one-hot encoded, and an XGBoost classifier scores fraud probability. SMOTE is applied to the training fold only after the train/test split to avoid evaluation leakage. The full source, tests, generated metrics, and executed notebook are available in [`motor-claims-triage`](https://github.com/GarethMackenzie/motor-claims-triage).

### Portfolio Model Performance
*Reproducible results from the public repository; these are demo-model results, not professional business outcomes.*

| Metric | Result |
|---|---|
| ROC-AUC | **0.719** |
| Precision when reviewing top 10% | **12.5%** |
| Fraud recall when reviewing top 10% | **26.9%** |
| False-positive rate at top-10% review capacity | **9.2%** |
| Lift over random review | **2.7×** |
| Recorded inference time | **~0.19 ms / claim** |

A fixed 0.5 probability threshold produces **95.2% accuracy but 0% fraud recall** on the current synthetic test set — an imbalanced-data trap documented rather than hidden. The case study therefore frames the operational decision around review capacity instead of an arbitrary probability cutoff.

![Fraud Detection Pipeline](https://raw.githubusercontent.com/GarethMackenzie/GarethMackenzie/main/fraud-detection-pipeline.gif)

*Conceptual portfolio flow: synthetic claim intake → XGBoost scoring → review-priority routing.*

**Dashboard source:** [`claims-dashboard.html`](https://github.com/GarethMackenzie/GarethMackenzie/blob/main/claims-dashboard.html) — an interactive Chart.js portfolio dashboard with explicit synthetic-data disclosure.

**Project stack:** Python · pandas · scikit-learn · XGBoost · imbalanced-learn (SMOTE) · matplotlib · Chart.js

## Core Capabilities

- Insurance claims analytics and operational decision support
- Fraud detection, risk scoring, and review prioritization
- Claims process redesign and operational efficiency
- SQL-based reporting and Power BI dashboards
- Regulatory-aware claims operations (POPIA)
- Cross-functional stakeholder communication

## Technical Stack

**Analytics & Programming** — Python · SQL · R · Excel (VBA)  
**Business Intelligence** — Power BI · Tableau  
**Machine Learning** — scikit-learn · XGBoost · SMOTE  
**Delivery & Tooling** — Streamlit · Git · GitHub

## Professional Experience

| Period | Role | Organization | Highlight |
|---|---|---|---|
| Oct 2023–Present | Insurance Specialist | Old Mutual Insure, Johannesburg | Led claims redesign cutting handling time by 40%; identified R500K+ in fraud; manage ~200 claims/month |
| Oct 2022–Jun 2023 | Claims Specialist | Auto & General Australia | Managed high-volume motor claims portfolio |
| Oct 2021–Sep 2022 | Customer Support Specialist | Bob Group, Bryanston | Optimized support workflows and process documentation |
| Sep 2018–Aug 2020 | Associate Claims Coordinator | Innovation Group South Africa | Policy administration across motor & agricultural portfolios |

## Education & Professional Development

- UNISA — Degree, Business Administration (2021–2025)
- UNISA — Higher Certificate in Insurance, NQF Level 5 (2018)
- South-West Gauteng College — Management, NQF Level 4 (2015–2017)
- Lean Six Sigma Black Belt
- Microsoft — Power BI Data Analyst
- Microsoft — Azure Data Scientist
- Oracle — Analytics Cloud 2025 Professional

*Public credential-verification links can be added as they are confirmed and available.*

## Let's Connect

Open to data, BI, insurance analytics, risk analytics, and analytics-engineering opportunities where domain knowledge and applied analytics need to work together.

| | |
|---|---|
| Email | [gamackenzie@live.com](mailto:gamackenzie@live.com) |
| LinkedIn | [Gareth Andrew Mackenzie](https://www.linkedin.com/in/gareth-andrew-mackenzie-50407b52/) |
| GitHub | [GarethMackenzie](https://github.com/GarethMackenzie) |

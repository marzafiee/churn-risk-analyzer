# Customer Churn Prediction & Retention ROI

Predict which customers are about to leave and recommend the interventions worth paying for.

## Problem

Most businesses only know a customer churned _after_ it happened, that is, when it's too late. This project predicts churn **30–60 days in advance** using behavioural signals, so retention teams can act _before_ revenue walks out the door.

## What This Project Does

| Layer              | Output                                               |
| ------------------ | ---------------------------------------------------- |
| **Prediction**     | Churn probability score per customer                 |
| **Prioritisation** | Ranked list of at-risk customers                     |
| **Cost-benefit**   | Which interventions are actually profitable to run   |
| **Business brief** | Revenue at risk, churn segments, recommended actions |

> _Since most churn projects stop at model accuracy, I decided to add a cost-benefit layer so one only acts where the ROI makes sense._

## Stakeholders

| Role              | How They Benefit                                   |
| ----------------- | -------------------------------------------------- |
| Marketing team    | Concentrate spend on highest-value interventions.  |
| Customer success  | Shift from reactive to proactive outreach.         |
| Business analysts | Tie model performance to measurable revenue saved. |

## Dataset

**Telco Customer Churn — [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)**
~7,000 rows · No scraping · No API · No cleaning hell

| Feature           | Description                        |
| ----------------- | ---------------------------------- |
| `tenure`          | Months as a customer               |
| `contract_type`   | Month-to-month, one year, two year |
| `monthly_charges` | Monthly bill amount                |
| `support_calls`   | Number of support interactions     |
| `services_used`   | Add-ons and products subscribed to |
| `churn`           | Target label (Yes / No)            |

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?logo=xgboost&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-11557C?logo=python&logoColor=white)

**Models used:** Logistic Regression · Random Forest · XGBoost
**Evaluation:** Confusion Matrix · Precision / Recall · ROC-AUC

## Results

> _To be updated after modelling_

| Metric                       | Score |
| ---------------------------- | ----- |
| Best model                   | —     |
| ROC-AUC                      | —     |
| Precision                    | —     |
| Recall                       | —     |
| Est. quarterly revenue saved | —     |

## Business Brief

> _One-page consulting summary TBA_

- **Revenue at risk:** —
- **Highest-churn segment:** —
- **Recommended intervention:** —

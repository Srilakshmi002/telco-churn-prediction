# Telco Customer Churn Prediction

A machine learning project to predict customer churn in a telecommunications company using **Logistic Regression**.

## Project Overview

Customer churn is a critical issue for telecom companies. This project analyzes the [IBM Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (7,043 customers) and builds a predictive model to identify at-risk customers.

- **Dataset**: 21 features including demographics, services, contract type, charges, and tenure.
- **Target**: Binary classification (`Churn`: Yes/No) — ~26.5% churn rate (imbalanced).
- **Model**: Logistic Regression (simple, interpretable baseline).
- **Performance**: ~80-82% accuracy on test set (good for baseline; focuses on interpretability).

Key insights:
- Month-to-month contracts strongly increase churn risk.
- Fiber optic internet users and electronic check payers are more likely to churn.
- Long-term contracts (1-2 years) and add-ons (online security, tech support) reduce churn.

## Requirements

- Python 3.12+
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

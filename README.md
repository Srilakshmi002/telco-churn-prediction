# Telco Customer Churn Prediction

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

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

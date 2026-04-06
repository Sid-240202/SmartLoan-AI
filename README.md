# 🚀 SmartLoan-AI: End-to-End Predictive Lending Framework

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![ML Framework](https://img.shields.io/badge/Model-Scikit--Learn-orange)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Business Overview
In the modern fintech landscape, credit risk assessment is the backbone of profitability. **SmartLoan-AI** is a machine learning solution designed to automate loan approval processes by predicting the probability of default with high precision. 

By leveraging historical applicant data (income, credit history, debt-to-income ratios), the model provides a data-driven decision-making tool for financial institutions.

## 🛠 Tech Stack
- **Languages:** Python (Pandas, NumPy)
- **Machine Learning:** Scikit-Learn, XGBoost
- **Explainability:** SHAP (Shapley Additive Explanations)
- **Deployment:** Streamlit (UI), Docker (Containerization)

## 📊 Feature Engineering & Insights
The model utilizes advanced feature engineering to increase predictive power:
* **Income-to-Loan Ratio:** Assessing the feasibility of repayment.
* **Credit History Maturity:** Weighting the age of credit lines.
* **Class Imbalance Handling:** Implemented SMOTE (Synthetic Minority Over-sampling Technique) to ensure the model doesn't bias toward "Approved" cases.



## 🧠 Explainable AI (XAI)
Unlike standard "black-box" models, SmartLoan-AI uses **SHAP** to provide local and global explanations. This ensures compliance with financial regulations (like GDPR's "Right to Explanation"), allowing the system to state exactly why an applicant was rejected.

## 🚀 How to Run
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Sid-240202/SmartLoan-AI.git](https://github.com/Sid-240202/SmartLoan-AI.git)
   cd SmartLoan-AI

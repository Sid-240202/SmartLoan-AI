# 🏦 SmartLoan-AI: Advanced Credit Risk Prediction

## 📌 Business Case
In the banking sector, identifying high-risk loan applicants is critical to maintaining low default rates. **SmartLoan-AI** uses Machine Learning to automate the approval process, providing a data-driven risk assessment score for each applicant.

## 🛠️ Data Engineering & Pipeline
* **Handling Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to address the class imbalance between approved and defaulted loans.
* **Feature Selection:** Utilized Correlation Heatmaps to remove redundant features and prevent multi-collinearity.
* **Scaling:** Implemented `StandardScaler` to normalize numerical features like Income and Loan Amount for consistent model convergence.



## 🧠 Model Architecture & Explainability
I compared **Logistic Regression**, **Decision Trees**, and **Random Forest**. The Random Forest model achieved the highest F1-score.
* **Explainable AI (XAI):** Integrated **SHAP** values to ensure "Right to Explanation" compliance, showing exactly which features (e.g., Credit History) led to a loan rejection.

## 📊 Performance Metrics
* **Accuracy:** 92.5%
* **Precision/Recall:** Optimized for Recall to minimize "False Positives" (Bad loans marked as Good).

---

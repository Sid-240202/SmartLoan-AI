# 🏦 SmartLoan-AI: Machine Learning for Credit Risk Assessment

## 📌 Project Overview
This project focuses on building a predictive model to automate the loan approval process. By analyzing applicant data such as income, education, and credit history, the model identifies the likelihood of a loan being repaid, helping financial institutions minimize credit risk.

## 🛠️ Technical Workflow
* **Data Cleaning:** Handled missing values and performed outlier detection on financial variables.
* **Exploratory Data Analysis (EDA):** Visualized correlations between applicant characteristics and loan status.
* **Feature Encoding:** Converted categorical variables (Gender, Married, Education) into numerical formats for model compatibility.
* **Model Selection:** Evaluated multiple classification algorithms, including Logistic Regression and Random Forest, to find the best balance between Precision and Recall.

## 📊 Key Results
* Achieved high classification accuracy on the test set.
* Identified 'Credit History' as the most significant predictor for loan approval.

## 🚀 Installation & Usage
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook notebooks/SmartLoan_Analysis.ipynb`

# 🏦 Loan Eligibility Prediction and Analysis

This project focuses on understanding loan applicant data and predicting whether a person is eligible for a loan. Using exploratory data analysis, statistical insights, and machine learning classification algorithms, I provide a data-driven solution to optimize loan approval processes.

## 📌 Objective

To analyze historical loan application data and build a model that predicts loan approval status. The insights will help financial institutions streamline and personalize their loan offerings.

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebooks
- Power BI (for dashboarding)
- Git & GitHub

## 📊 Data Overview

The dataset contains ~600 records with features like:
- Applicant Income
- Education Level
- Property Area
- Credit History
- Loan Amount
- Employment Status

Target Variable: `Loan_Status`

## 🔍 Exploratory Data Analysis (EDA)

Key steps:
- Distribution of income and loan amounts
- Impact of credit history on loan approval
- Loan approval rate across property area and gender
- Missing value treatment and feature engineering

> ✅ Insights:
> - Applicants with a credit history have a ~80% higher approval rate.
> - Urban applicants with graduate education and stable income have higher approval odds.

## 🧠 Modeling

- **Decision Tree Classifier** (baseline)
- **Logistic Regression**
- **Random Forest Classifier**
- Evaluation using Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## 📈 Performance

| Model | Accuracy | Precision | Recall |
|-------|----------|-----------|--------|
| Decision Tree | 0.79 | 0.77 | 0.81 |
| Logistic Regression | 0.82 | 0.83 | 0.80 |
| Random Forest | **0.84** | **0.85** | **0.83** |

## 📊 Power BI Dashboard

- Dynamic visual exploration of approval rate by geography, income, credit history
- Insights for loan officers to target high-potential applicants

![Loan Dashboard](images/powerbi_dashboard.png)

## 📌 Business Recommendations

- Prioritize applicants with good credit history and steady income
- Offer financial literacy programs to self-employed and non-graduates
- Tailor offers based on geographic loan performance trends

## 🗂️ Repository Structure


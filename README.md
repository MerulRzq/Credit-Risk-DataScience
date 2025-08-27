# German Credit Risk Data Analysis

## 📊 Project Overview
This project we’ll build a Credit Risk Modeling system using Python and Machine Learning from scratch. Analyzes the German Credit Risk dataset to identify key factors that influence a customer's credit risk assessment. The analysis explores relationships between various customer attributes (age, job, savings, credit purpose) and their associated risk level (good vs. bad). Learn how to process real-world financial data, apply Scikit-learn for model training, and deploy an interactive dashboard with Streamlit

## 🎯 Objectives
- Perform exploratory data analysis (EDA) on credit risk data.
- Identify patterns and relationships between customer features and credit risk.
- Visualize distributions and correlations in the data.
- Understand which factors are most indicative of high-risk applicants.

## 🔍 Key Insights & Findings

1. Risk Distribution

- The dataset shows a class imbalance with approximately 70% good risks and 30% bad risks.
- This imbalance is important to consider for predictive modeling.

2. Categorical Features Analysis

- Purpose: Loans for cars and furniture show higher good risk rates.
- Savings/Checking Accounts: Applicants with moderate to rich account balances tend to have better risk assessments.
- Job Level: Higher job qualification levels correlate with lower risk.
- Housing: Home owners generally have better credit risk profiles.

3. Numerical Features Analysis

- Credit Amount: Higher credit amounts show slightly higher risk tendencies.
- Duration: Longer loan durations are associated with higher risk levels.
- Age: Younger applicants (20-30) show higher risk compared to middle-aged applicants.

4. Notable Correlations

- Strong relationship between account balances (savings/checking) and risk assessment.
- Purpose of loan significantly influences risk outcome.
- Job stability and housing situation are important indicators of creditworthiness.

## 🛠️ Technical Implementation

- Python 3.11.4
- Pandas - Data manipulation and analysis
- NumPy - Numerical computations
- Matplotlib - Basic visualizations
- Seaborn - Advanced statistical visualizations

## Key Analysis Steps

- Data Loading & Cleaning
- Handled missing values in account features
- Verified data types and distributions
- Exploratory Data Analysis
- Univariate analysis of all features
- Bivariate analysis against risk target
- Correlation analysis between numerical features
- Data Visualization
- Count plots for categorical feature distributions
- Box plots and violin plots for numerical feature analysis
- Risk comparison across all features

## 📈 Visualizations

The analysis includes comprehensive visualizations showing:
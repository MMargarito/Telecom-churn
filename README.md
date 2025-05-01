# Telecom-churn-project

Data Analysis Portfolio Project: Customer Churn Prediction for a Telecom Company
Problem Statement:
I am a data analyst at a telecom company facing high customer churn rates. The company wants to understand why customers are leaving and develop strategies to retain them. 
Your task is to analyze a customer dataset, identify key factors contributing to churn, and build a predictive model to flag at-risk customers.

Dataset Description:
Use the dataset (telecom_churn.csv) containing 10,000 customer records with the following columns:  

CustomerID: Unique identifier for each customer.  
Tenure: Number of months the customer has been with the company (0–72).  
MonthlyCharges: Monthly bill amount (USD).  
TotalCharges: Total amount billed to the customer (USD).  
Contract: Contract type (Month-to-month, One-year, Two-year).  
PaymentMethod: Payment method (Electronic check, Mailed check, Bank transfer, Credit card).  
InternetService: Type of internet service (DSL, Fiber optic, No).  
OnlineSecurity: Whether the customer has online security (Yes, No, No internet).  
TechSupport: Whether the customer has tech support (Yes, No, No internet).  
Churn: Whether the customer churned (Yes, No).  
Demographics: Age (18–80), Gender (Male, Female),
SeniorCitizen (0 or 1).

Project Objectives:
Exploratory Data Analysis (EDA):  
Analyze the distribution of churn across different features (e.g., contract type, monthly charges, tenure).  
Identify patterns or trends (e.g., Are customers with higher bills more likely to churn?).  
Visualize key insights using appropriate charts (e.g., bar plots, histograms, correlation heatmaps).

Feature Engineering:  
Handle missing or inconsistent data (e.g., impute missing TotalCharges).  

Create new features (e.g., AverageMonthlyCharges = TotalCharges/Tenure, HighBillFlag for customers with MonthlyCharges > $75).  
Encode categorical variables (e.g., one-hot encoding for Contract, label encoding for Churn).

Statistical Analysis:  
Perform hypothesis testing to check if churn rates differ significantly across contract types or payment methods (e.g., chi-square test).  
Analyze correlations between numerical features (e.g., Tenure vs. TotalCharges) and churn.

Business Recommendations:  
Based on your findings, suggest actionable strategies to reduce churn (e.g., targeted discounts for month-to-month contract holders).  
Quantify the potential impact (e.g., “Retaining 10% of at-risk customers could save $X annually”).

Deliverables:  
A Jupyter Notebook or R script with well-commented code covering EDA, feature engineering, and statistical analysis.  
A slide deck or report summarizing key findings, visualizations, model performance, and recommendations (5–10 slides or 2–3 pages).  

Tools and Libraries:  
Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn,

Challenges to Address:  
Handle class imbalance (e.g., only 20% of customers churn).  
Deal with multicollinearity between features (e.g., TotalCharges and Tenure).  

Success Criteria:  
Provide clear, data-driven recommendations that align with business goals.  
Ensure the analysis is reproducible and well-documented for portfolio showcasing.

This project demonstrates skills in data cleaning, EDA, statistical analysis, and business communication, making it a strong addition to your portfolio.

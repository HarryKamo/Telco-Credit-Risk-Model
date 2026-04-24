# 📊 Telco Credit Risk Prediction Model

## 🚀 Project Overview
This project explores how telecommunications behavioural data can be used to predict customer credit risk. The goal is to explore how telco usage patterns can be used as an alternative approach to credit scoring. It demonstrates an end-to-end machine learning pipeline, from data generation to model evaluation.


## 🎯 Problem Statement
Traditional credit scoring relies heavily on financial history. However, many individuals lack formal credit records.
This project investigates whether telco behavioural data (usage patterns, recharge behaviour, and account activity) can be used as an alternative indicator for credit default risk prediction.

## 📁 Dataset Description
A simulated dataset was created to mimic real-world telecom customer behaviour, including:

- Monthly recharge averages
- Data usage (GB)
- Call minutes
- SMS activity
- Late recharge frequency
- Account tenure
- Default outcome (target variable)

## ⚙️ Project Workflow

1. Data simulation and generation  
2. Data preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature selection  
5. Train-test split  
6. Logistic Regression model training  
7. Model evaluation  

## 🤖 Machine Learning Model
- Logistic Regression (baseline classification model)

## 📊 Model Performance
- Achieved strong predictive accuracy of 0.965 on test data
- Behavioural features showed strong correlation with default risk

## 📌 Key Insights
- Customers with frequent late recharges show higher default probability  
- Short account tenure is associated with increased risk  
- Usage behaviour can be a strong predictor of financial reliability  

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

## 📈 Visual Analysis
See below for key visual insights from the dataset and model results.

## 🚀 Future Improvements
- Implement Random Forest and XGBoost models  
- Add ROC-AUC evaluation  
- Build interactive dashboard (Streamlit)  
- Deploy as a web application  

## 👨‍💻 Author
Built as part of a data science portfolio focused on credit risk modelling and financial inclusion analytics using telecommunications data.

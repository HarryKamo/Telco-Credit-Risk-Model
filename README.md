# Telco Credit Risk Prediction Model

## 📊 Project Overview
This project builds a machine learning model that predicts customer credit risk using simulated telecommunications behavioural data. The goal is to explore how telco usage patterns can be used as an alternative approach to credit scoring.

## 🎯 Problem Statement
Traditional credit scoring relies on financial history. This project explores whether telecom behavioural data (usage patterns, recharge behaviour, and account activity) can be used to predict default risk.

## 📁 Dataset
A simulated dataset was created containing:
- Monthly recharge averages
- Data usage (GB)
- Call minutes
- SMS activity
- Late recharge frequency
- Account tenure
- Default label (target variable)

## ⚙️ Methodology
1. Data simulation and generation
2. Exploratory Data Analysis (EDA)
3. Feature selection
4. Train-test split
5. Logistic Regression model training
6. Model evaluation

## 🤖 Model Used
- Logistic Regression

## 📈 Results
- Model achieved high accuracy of 0.965 on test data
- Behavioural features showed strong predictive power for default risk

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 💡 Key Insight
Telecommunications behavioural data can potentially be used as an alternative indicator for credit risk assessment.

## 🚀 Future Improvements
- Use Random Forest / XGBoost models
- Add ROC-AUC evaluation
- Build interactive dashboard (Streamlit)
- Deploy as a web app

## 👨‍💻 Author
Built as part of a data science learning portfolio focused on credit risk and financial inclusion analytics.

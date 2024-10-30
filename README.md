# Financial Data Analysis and Modeling Projects

This repository contains two projects aimed at understanding financial data through linear regression and risk estimation techniques.

---

## Project 1: Housing Price Prediction Using Linear Regression

This project explores **linear regression** and **regularization techniques** to predict housing prices using the Ames, Iowa Housing dataset, which contains 1460 observations with 79 features describing residential properties. 

### Key Steps:
1. **Data Preprocessing**: Import and clean data, apply transformations to achieve normality in the target variable, and utilize one-hot encoding for categorical variables.
2. **Model Development**: Train a linear regression model using the numerical features to predict housing prices.
3. **Advanced Techniques**: 
   - Apply matrix algebra to compute regression coefficients and their standard errors.
   - Extend the model to include polynomial features and explore higher-order regression techniques.
4. **Regularization Methods**: Implement Ridge, Lasso, and pseudoinverse techniques with cross-validation, comparing in-sample and out-of-sample performance.

This project is designed to assess various model evaluation metrics, such as MSE and R², to determine the optimal predictive model.

---

## Project 2: Credit Risk Analytics for Consumer Loans

This project focuses on **credit risk modeling** for consumer loans, using simulated borrower data with three key features: age, income, and employment status. The goal is to develop risk profiles and identify “good” borrowers based on repayment probabilities.

### Key Steps:
1. **Data Simulation**: Generate synthetic data for borrower characteristics and create two target labels indicating borrower risk levels.
2. **Logistic Regression and SVM Models**: 
   - Train logistic regression and SVM models to predict repayment probability, using cross-entropy loss as the evaluation metric.
   - Apply SVM with Platt scaling for probability estimation.
3. **Lending Strategy Simulation**: 
   - Simulate three lending strategies and evaluate expected profit, loss, and Value at Risk (VaR) over a range of market scenarios.
   - Compare strategies by evaluating profit distributions under different selection criteria.

Through this project, we aim to understand model applications in credit scoring, risk management, and profitability analysis.

---

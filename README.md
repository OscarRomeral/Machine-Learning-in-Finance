# Financial Data Analysis and Modeling Projects

This repository contains three projects focused on financial data analysis, predictive modeling, and advanced hedging strategies using machine learning techniques.

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

This project assesses various model evaluation metrics, such as MSE and R², to determine the optimal predictive model.

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

This project highlights model applications in credit scoring, risk management, and profitability analysis.

---

## Project 3: Deep Hedging of Call Options

This project implements **deep hedging** to manage risk associated with a call option, leveraging the methodology outlined in:

> [Buehler et al., 2019] Buehler, H., Gonon, L., Teichmann, J., and Wood, B. (2019). Deep hedging.  
> Quantitative Finance, 19(8):1271–1291.

### Key Steps:
1. **Theoretical Framework**: Review and implement the deep hedging framework, focusing on the non-linear optimization problem that integrates market frictions and transaction costs into the hedging strategy.
2. **Data Generation**:
   - Simulate asset price trajectories using stochastic differential equations (e.g., Black-Scholes model or Heston model).
   - Generate synthetic options data to train the hedging network.
3. **Neural Network Architecture**:
   - Develop a deep learning model to compute the hedging strategy by minimizing the terminal risk metric, such as PnL variance or CVaR.
4. **Comparison with Traditional Methods**:
   - Compare the deep hedging performance with traditional Black-Scholes delta hedging and evaluate under varying market conditions.
5. **Evaluation Metrics**:
   - Assess hedging effectiveness through metrics such as variance reduction, mean squared hedging error, and tail risk measures.

This project demonstrates how machine learning techniques can enhance hedging strategies by incorporating real-world considerations, including transaction costs and market frictions.

---

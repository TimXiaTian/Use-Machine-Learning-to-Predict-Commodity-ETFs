## Machine Learning and Financial Applications

### Overview

This project is part of the Master of Science in Quantitative Finance program (AY2023-24) and focuses on employing various machine learning techniques to predict the movements of three diverse stock index prices. The objective is to design a portfolio strategy integrating stacking models for accurate predictions and Particle Swarm Optimization (PSO) for optimal weight allocation.

### Table of Contents
[TOC]

### Executive Summary

This project investigates the application of machine learning techniques to predict the price movements of three ETFs: DBA, GLD, and USO. A stacking model approach was used, combining predictions from base models to improve accuracy. The Particle Swarm Optimization (PSO) algorithm was employed for optimal asset allocation, aiming to maximize risk-adjusted returns.

### Economic Significance
The project emphasizes the importance of accurate market predictions and risk management for investors, financial institutions, and traders. The findings aim to enhance investment strategy optimization, risk management, portfolio allocation, and trading algorithms, contributing to more informed economic forecasting and strategic planning.

### Data Cleaning and Feature Engineering
The project utilizes price data from Yahoo! Finance and economic indicators from the US Federal Reserve Economic Data (FRED) website. Key steps include:
- Data processing and creation of technical indicators.
- Feature selection using Principal Component Analysis (PCA) and Mutual Information (MI).
- Analysis of data correlations and feature relevance.

### Model Selection and Hyperparameter Tuning
The project employs a stacking model framework with the following components:
- **Base Models**: Random Forest, Extra Trees, Gradient Boosting, Support Vector Machine, Naive Bayes.
- **Meta Model**: AdaBoost Classifier.
- Hyperparameter optimization using Bayesian optimization with cross-validation.

### Results and Portfolio Optimization
The results indicate that Gradient Boosting and Ensemble Stacking models performed best. The PSO algorithm was used for portfolio optimization, leading to a Sharpe ratio of 1.268 for the final portfolio. The portfolio optimization strategy demonstrated effective risk-adjusted returns, with visualizations of the daily return rates and final asset allocation.

### Conclusion and Future Improvements
The project successfully developed a machine learning-driven trading strategy, with future improvements suggested in dynamic rebalancing, additional optimization algorithms, stress testing, transaction cost integration, and further exploration of return predictions.

### How to Use This Repository
1. **Data Preparation**: Ensure all required datasets are available and properly formatted.
2. **Model Training**: Run the provided scripts for data cleaning, feature engineering, and model training.
3. **Hyperparameter Tuning**: Utilize the hyperparameter tuning scripts to optimize model performance.
4. **Portfolio Optimization**: Apply the PSO algorithm for asset allocation based on the model predictions.
5. **Evaluation**: Review the results, visualizations, and performance metrics.

### Dependencies
- Python
- Pandas
- Numpy
- Scikit-learn
- Yahoo! Finance API
- US Federal Reserve Economic Data (FRED)
- Matplotlib
- Scikit-optimize

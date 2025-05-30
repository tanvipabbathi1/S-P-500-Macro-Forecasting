# S&P 500 Macro Forecasting 

Predictive models to analyze the impact of macroeconomic indicators on S&P 500 movement using advanced statistical and machine learning techniques.

This project was completed as part of a group for a course at the University of Pennsylvania.

## Overview

This project explores whether macroeconomic indicators—such as consumer spending, TSA checkpoint volume, and the Federal Funds Rate—can be used to predict the daily movement of the S&P 500. We investigate relationships between key economic sectors and market behavior to answer high-impact questions for investors.

### Goals

- Identify macroeconomic sectors most correlated with S&P 500 movements.
- Develop models to forecast daily S&P 500 direction.
- Evaluate model performance and interpret economic implications.

## Methodology

- **Data Sources**: Bloomberg Terminal, Bloomberg Second Measure, FRED (Federal Reserve Economic Data)
- **Modeling Techniques**:
  - Logistic Regression
  - LASSO Regularization
  - K-Means Clustering
  - Feature selection based on economic intuition and statistical relevance
- **Transformations**: Box-Cox, log, square root (for skew correction)

## Key Insights

- Specific indicators like debit card spending, TSA data, and interest rate shifts showed significant correlation with SPX movement.
- Logistic regression on select sectors achieved improved accuracy over baseline random walk models.

## Technologies Used

- **R**
- **ggplot2**, **dplyr**, **MASS**, **glmnet**
- **Bloomberg** and **FRED** data ingestion

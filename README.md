# Credit Card Approval Prediction

This project analyzes credit card approval decisions using exploratory data analysis, feature engineering, and machine learning classification models.

## Objective

The goal was to identify the strongest drivers of credit card approval and compare predictive modeling approaches based on both performance and interpretability.

## Dataset

The dataset included 690 credit card applications and 15 applicant variables across:

- Financial indicators
- Employment indicators
- Applicant information
- Bank relationship variables
- Approval outcome target variable

## Methods

The analysis included:

- Data cleaning and preparation
- Exploratory data analysis
- Feature transformation
- Correlation analysis
- Feature selection
- Classification modeling
- Model evaluation
- Bias analysis

## Models Tested

- Logistic Regression
- LASSO Regression
- Random Forest
- Gradient Boosting
- Naive Bayes
- Support Vector Machine

## Key Findings

- Prior Default was the strongest predictor of approval outcomes.
- Employment status, credit score, and years employed were meaningful predictors.
- Random Forest achieved the strongest predictive performance.
- LASSO Regression provided the clearest interpretability.
- Approval rates varied across demographic and industry groups, highlighting the need for fairness monitoring.

## Final Recommendation

Use Random Forest when predictive performance is the priority and LASSO Regression when interpretability and stakeholder explanation are most important.

## Files

- `credit_card_approval_modeling.ipynb` — full modeling notebook
- `credit_card_approval_presentation.pdf` — final project presentation

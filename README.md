# Multiple Linear Regression – Multi-Channel Marketing Analysis

## Project Overview

This project analyzes the relationship between different marketing channels and sales performance using Multiple Linear Regression. The goal is to determine how advertising channels influence sales, evaluate the statistical significance of predictors, and provide evidence-based recommendations for marketing budget allocation.

---

## Dataset Description

The dataset contains marketing campaign information including:

- TV advertising category
- Radio advertising spend
- Social Media advertising spend
- Influencer category
- Sales (target variable)

The objective is to understand how these marketing factors contribute to changes in sales performance.

---

## Analysis Goals

The analysis was performed to:

- Explore relationships between marketing variables and sales
- Detect multicollinearity among independent variables
- Build a Multiple Linear Regression model using OLS
- Evaluate model performance using R-squared and Adjusted R-squared
- Determine significant predictors using p-values
- Validate regression assumptions using diagnostic plots
- Translate statistical findings into business recommendations

---

## Data Preprocessing

The following preprocessing steps were performed:

- Categorical variables were encoded into numerical format
- Numerical variables were scaled
- Independent variables were prepared for regression analysis

Predictor variables used:

- TV
- Radio
- Social Media
- Influencer

Target variable:

- Sales

---

## Multicollinearity Check

Multicollinearity was assessed using:

- Correlation matrix
- Variance Inflation Factor (VIF)

The VIF analysis showed that predictors had acceptable multicollinearity levels, allowing all variables to be retained in the regression model.

---

## Model Development

A Multiple Linear Regression model was built using the `statsmodels` OLS method.

The final model predicts Sales based on:

- TV advertising category
- Radio advertising
- Social Media advertising
- Influencer category

---

## Model Performance

The model achieved:

- R-squared: 0.744
- Adjusted R-squared: 0.742

This indicates that approximately 74% of the variation in sales can be explained by the selected marketing variables.

The overall regression model was statistically significant.

---

## Key Findings

Radio advertising was identified as the strongest significant predictor of sales.

- Radio showed a strong positive relationship with Sales.
- TV was statistically significant but showed a negative association after controlling for other variables.
- Social Media and Influencer variables were not statistically significant predictors in the final model.

---

## Business Recommendation

Based on the analysis, marketing resources should prioritize Radio advertising due to its strong positive impact on sales. TV campaigns should be reviewed and optimized, while Social Media and Influencer strategies should be evaluated further to determine their return on investment.

Future marketing decisions should continue to be guided by performance data and regular model evaluation.

---

## Model Diagnostics

Regression assumptions were evaluated using:

- Residual vs fitted plot (Linearity)
- Q-Q plot (Normality)
- Residual spread plot (Homoscedasticity)

The diagnostic plots showed that the model assumptions were reasonably satisfied.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy scikit-learn

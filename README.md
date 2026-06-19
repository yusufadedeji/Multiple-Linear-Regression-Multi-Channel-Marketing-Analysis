# Multiple Linear Regression for Multi-Channel Marketing Budget Optimization

## Project Overview

This project applies Multiple Linear Regression (MLR) to evaluate the impact of different marketing channels on sales performance. The objective is to build a statistically robust model that explains how investments in TV, Radio, and Social Media advertising influence sales and to generate evidence-based recommendations for marketing budget allocation.

The analysis was conducted using Python and the `statsmodels` library to perform Ordinary Least Squares (OLS) regression, evaluate model performance, validate regression assumptions, and interpret the contribution of each marketing channel while holding other variables constant.

---

## Dataset Description

The dataset contains advertising expenditure across three marketing channels and their corresponding sales outcomes.

### Variables

| Variable     | Description                                                     |
| ------------ | --------------------------------------------------------------- |
| TV           | Advertising expenditure on TV campaigns                         |
| Radio        | Advertising expenditure on radio campaigns                      |
| Social Media | Advertising expenditure on social media campaigns               |
| Influencer   | Influencer category associated with the campaign                |
| Sales        | Sales generated from the marketing activities (target variable) |

The goal is to determine how different marketing channels contribute to sales performance and identify the most effective areas for budget allocation.

---

## Project Objectives

This project aims to:

* Perform exploratory data analysis (EDA)
* Detect multicollinearity among predictors
* Build a Multiple Linear Regression model
* Evaluate model performance using R² and Adjusted R²
* Assess statistical significance using p-values
* Validate regression assumptions using diagnostic plots
* Interpret regression coefficients in a business context
* Generate data-driven recommendations for marketing budget allocation

---

## Analysis Workflow

The following steps were performed:

### 1. Exploratory Data Analysis (EDA)

* Dataset inspection
* Missing value assessment
* Duplicate checking
* Summary statistics
* Pairwise relationship visualization

### 2. Multicollinearity Assessment

* Correlation matrix analysis

### 3. Model Development

Two approaches were implemented:

* Scikit-learn Linear Regression
* Statsmodels Ordinary Least Squares (OLS) Regression

### 4. Model Evaluation

The following performance metrics were calculated:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R²
* Adjusted R²
* Predictor p-values

### 5. Assumption Validation

Regression assumptions were evaluated using diagnostic plots:

* Linearity
* Homoscedasticity
* Normality of residuals

### 6. Business Interpretation

The regression coefficients were interpreted to quantify the effect of each marketing channel on sales while holding the remaining channels constant.

---

## Key Findings

* The model explained a substantial proportion of the variability in sales.
* TV advertising showed the strongest contribution to sales performance.
* Predictor significance was evaluated using p-values.
* Diagnostic plots indicated that the model assumptions were reasonably satisfied, with only minor deviations observed.
* The results support data-driven marketing budget allocation decisions.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* SciPy

---

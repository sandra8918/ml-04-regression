# Project 4 – Titanic Fare Prediction Using Regression

## Introduction

For this project, I applied regression techniques to predict the **fare** paid by Titanic passengers. Unlike classification problems that predict categories, regression predicts continuous numerical values. I explored several regression models and compared their performance using multiple evaluation metrics.

---

# Phase 4 – Technical Modification

## What I Changed

I created my own regression notebook based on the instructor's example and modified it to analyze the Titanic dataset. I compared multiple regression models instead of using only a single linear regression model.

## Why I Chose This Change

I wanted to better understand how different regression algorithms perform on the same dataset and determine whether regularization could improve prediction accuracy.

## How I Verified It Worked

I successfully executed the notebook without errors. The notebook generated regression metrics and completed all model comparisons successfully.

## Results

The notebook produced evaluation metrics (RMSE, MAE, and R²) for multiple regression models. The results showed that combining multiple features improved prediction performance compared to using only a single feature.

---

# Phase 5 – Custom Project

## Dataset

I used the Titanic dataset available through the Seaborn library.

The target variable for this project was **Fare**, which is a continuous numerical value suitable for regression.

## Features

The following features were evaluated:

- Age
- Family Size
- Sex

Several combinations of these features were tested to determine which produced the best predictions.

## Modeling Approach

This project uses **supervised learning** because the target values are known during training.

The regression models included:

- Linear Regression
- Ridge Regression
- Elastic Net
- Polynomial Regression

## Evaluation

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² (Coefficient of Determination)

Among the linear regression models, the combination of **Age, Family Size, and Sex** produced the strongest performance.

The regularized models produced similar results while helping reduce the possibility of overfitting.

## Summary

This project demonstrated how regression models can be used to predict continuous numerical values. It also showed how feature selection influences prediction accuracy and how regularization helps improve model generalization.

Working through this project strengthened my understanding of regression analysis, model evaluation, and feature engineering. These techniques can be applied to many real-world prediction problems such as housing prices, insurance costs, sales forecasting, and financial analysis.

---

# Future Work

If I continued this project, I would include additional variables such as passenger class (`pclass`), embarkation port, and cabin information to improve prediction accuracy. I would also experiment with different regularization parameters and additional regression models.

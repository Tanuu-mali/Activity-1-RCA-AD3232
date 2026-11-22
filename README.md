# Activity 1: Multiple Linear Regression – Concrete Compressive Strength Prediction

## Project Overview

This project implements Linear Regression to predict the compressive strength of concrete using multiple input features.

The objective is to understand the working of Simple and Multiple Linear Regression, calculate regression coefficients manually, evaluate model performance and develop a user-input-based prediction system.

## Dataset Information

**Dataset Name:** Concrete Compressive Strength

**Source:** UCI Machine Learning Repository

**Dataset Link:** https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength

**Total Observations:** 1,030 (before any cleaning)

**Total Columns:** 9

**Input Features:** 8

**Target Variable:** Concrete Compressive Strength

**Target Unit:** MPa

## Input Features

| Feature | Description | Unit |
|---|---|---|
| Cement | Cement quantity | kg/m³ |
| Blast Furnace Slag | Slag quantity | kg/m³ |
| Fly Ash | Fly ash quantity | kg/m³ |
| Water | Water quantity | kg/m³ |
| Superplasticizer | Additive quantity | kg/m³ |
| Coarse Aggregate | Coarse aggregate quantity | kg/m³ |
| Fine Aggregate | Fine aggregate quantity | kg/m³ |
| Age | Concrete curing age | Days |
| Strength | Concrete compressive strength | MPa |

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Methodology

The following steps were performed:

1. Dataset loading and inspection.
2. Data cleaning and preprocessing.
3. Exploratory Data Analysis.
4. Scatter plot visualisation.
5. Correlation matrix and heatmap.
6. Manual calculation of Multiple Linear Regression using the normal equation.
7. Verification of manual calculations using Scikit-learn.
8. Training and testing data split (80:20).
9. Simple Linear Regression using one input feature.
10. Multiple Linear Regression using eight input features.
11. Regression coefficient interpretation.
12. Actual vs predicted comparison.
13. Model evaluation using MAE, MSE, RMSE, R² and Adjusted R².
14. Residual analysis.
15. Multicollinearity analysis using VIF.
16. Checking Linear Regression assumptions.
17. Interactive prediction using user-provided input values.

## Model Evaluation

The models were evaluated using the following metrics:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R²:** Coefficient of Determination
- **Adjusted R²:** Adjusted Coefficient of Determination



## User Input Prediction System

The project includes an interactive prediction system that accepts the following user inputs:

- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age

The trained Multiple Linear Regression model predicts the concrete compressive strength in MPa.

## Conclusion

This project demonstrates how Linear Regression can be used to predict concrete compressive strength using multiple input variables.

Simple and Multiple Linear Regression models were compared to investigate whether additional features improve prediction performance.

The project also demonstrates manual regression calculations, coefficient interpretation, residual analysis and multicollinearity checking.

The final implementation provides an interactive system for predicting concrete strength based on user-provided mixture details.

**Note:** This project is developed for academic and educational purposes and should not be used as a substitute for actual concrete strength testing or structural engineering validation.



## Author

**Student Name:** Tanvi Mali

**Roll Number:** AD3232

**Course:** Artificial Intelligence and Data Science

**Activity:** Activity 1 – Regression Algorithms


## GitHub Submission

Submitted to: [@complexiota](https://github.com/complexiota)
Student repository- https://github.com/Tanuu-mali/Activity-1-RCA-AD3232

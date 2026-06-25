# House Price Prediction - Analytical Report

## Objective

Predict house prices using multiple regression models and compare their performance.

## Dataset

* California Housing Dataset
* Records: 20,640
* Features: 8
* Target: HousePrice
* Missing Values: 0

## Preprocessing

* Feature and target separation
* Train-Test Split (80:20)
* Feature Scaling using StandardScaler

## Models Used

* Linear Regression
* Polynomial Regression
* Ridge Regression
* Lasso Regression

## Results

| Model                 | MAE   | MSE   | R²    |
| --------------------- | ----- | ----- | ----- |
| Linear Regression     | 0.533 | 0.556 | 0.576 |
| Polynomial Regression | 0.467 | 0.464 | 0.646 |
| Ridge Regression      | 0.533 | 0.556 | 0.576 |
| Lasso Regression      | 0.533 | 0.554 | 0.577 |

## Key Findings

* Polynomial Regression achieved the best performance.
* Lowest MAE and MSE were obtained using Polynomial Regression.
* Highest R² Score (0.646) was achieved by Polynomial Regression.
* Ridge and Lasso performed similarly to Linear Regression.
* Non-linear relationships exist in the housing dataset.

## Conclusion

Polynomial Regression was selected as the best model for house price prediction.

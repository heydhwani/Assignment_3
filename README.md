# House Price Prediction using Regression Models

A machine learning project that predicts house prices using multiple regression algorithms and compares their performance.

## Models Used

* Linear Regression
* Polynomial Regression
* Ridge Regression
* Lasso Regression

## Dataset

* California Housing Dataset
* 20,640 records
* 8 input features
* 1 target variable (HousePrice)

## Evaluation Metrics

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* R² Score

## Best Model

**Polynomial Regression**

| MAE   | MSE   | R²    |
| ----- | ----- | ----- |
| 0.467 | 0.464 | 0.646 |

## Project Structure

```text
Assignment_3/
│
├── data/
│   └── housing.csv
│
├── notebooks/
│   └── house_price_prediction.ipynb
│
├── reports/
│   └── analytical_report.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

## Key Outcome

Polynomial Regression achieved the highest R² score and produced the most accurate house price predictions among all evaluated models.

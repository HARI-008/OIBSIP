# Car Price Prediction

## Objective

The objective of this project is to predict the selling price of used cars using machine learning techniques.

## Dataset

The project uses the Car Details from CarDekho dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Data Preprocessing

The dataset was cleaned by removing duplicate records and handling missing values.

Feature engineering was performed to extract:

- Car brand
- Car age
- Mileage
- Engine capacity
- Maximum power
- Torque

## Exploratory Data Analysis

EDA was performed using:

- Price distribution
- Scatter plots
- Box plots
- Correlation heatmap

## Machine Learning Models

Two regression models were used:

1. Linear Regression
2. Random Forest Regressor

## Evaluation Metrics

The models were evaluated using:

- MAE
- RMSE
- R² Score

## Results

Random Forest Regressor performed better than Linear Regression.

### Linear Regression

- MAE: ₹133,389
- RMSE: ₹260,212
- R²: 0.6913

### Random Forest Regressor

- MAE: ₹72,037
- RMSE: ₹123,556
- R²: 0.9304

## Conclusion

The Random Forest Regressor provided the better performance for predicting used-car selling prices.

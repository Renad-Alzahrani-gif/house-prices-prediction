# House Prices Prediction

A machine learning project for predicting house prices using the house prices dataset.

## Project Overview

The goal of this project is to build a regression model that predicts house prices based on different property features.

## Dataset

The project uses the house prices dataset, with `SalePrice` as the target variable.

## Workflow

The project follows these main steps:

1. Split the data into training and validation sets.
2. Identify numerical and categorical features.
3. Handle missing values using median imputation for numerical features and most-frequent imputation for categorical features.
4. Convert categorical features using One-Hot Encoding.
5. Build a preprocessing and model pipeline.
6. Train an XGBoost regression model.
7. Evaluate the model using MAE and R².
8. Use 5-Fold Cross Validation to evaluate model performance.
9. Analyze feature importance and prediction errors.
10. Compare actual and predicted house prices.

## Model

The main model used in the project is **XGBoost Regressor**.

Main parameters include:

* `n_estimators = 1000`
* `learning_rate = 0.03`
* `max_depth = 4`
* `subsample = 0.8`
* `colsample_bytree = 0.8`

## Evaluation

The model is evaluated using:

* **Mean Absolute Error (MAE)**
* **R² Score**
* **5-Fold Cross Validation**

The project also analyzes the largest prediction errors and the percentage of cases where the model under-predicted the actual house price.

## Tools

* Python
* Pandas
* Scikit-learn
* XGBoost
* Matplotlib
* Google Colab
* GitHub

## Project File
House_Prices_Prediction.ipynb contains the complete analysis, preprocessing, model training, evaluation, and results.

`House_Prices_Prediction.ipynb` contains the complete analysis, preprocessing, model training, evaluation, and results.


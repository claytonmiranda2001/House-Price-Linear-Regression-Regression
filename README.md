# House Price Prediction – Linear Regression
## Project Objective

The objective of this project is to build a Linear Regression model to predict house prices using a dataset obtained from Kaggle.

## Data Preprocessing

* No missing values were found
* No outliers were identified based on boxplot analysis

These conditions ensure a clean dataset and contribute to model stability and performance.

## Data Splitting

The dataset was divided into:

* 80% Training set
* 10% Validation set
* 10% Test set

## Data Standardization

Applied StandardScaler from scikit-learn. Ensured all features are on the same scale, improving model performance

## Model

* Linear Regression:
Used as the main model for predicting continuous values (house prices)

## Model Evaluation

* R²: 0.9983
* MSE: 112,090,090.2042
* RMSE: 10,587.2608
* MAPE: 0.0174 (1.74%)

## Metric Interpretation

* R² (Coefficient of Determination)

Explains how much variance in the target variable is captured by the model.

0.9983 → ~99.83% explained variance
Indicates an almost perfect fit

* MSE (Mean Squared Error)

Measures the average squared error between predictions and actual values.

More sensitive to large errors

* RMSE (Root Mean Squared Error)

Represents the average prediction error in the same unit as house prices.

Predictions deviate by approximately 10.5k on average

* MAPE (Mean Absolute Percentage Error)

Measures the average percentage error.

1.74% → very high accuracy

## Conclusion

The model achieved excellent performance, with very high R² and low error metrics.
This indicates a strong ability to accurately predict house prices and a very good fit to the data.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

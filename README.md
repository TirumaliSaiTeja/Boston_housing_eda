# Boston_housing_eda
Exploratory analysis on boston_housing dataset

**Attribute Information:**
CRIM: per capita crime rate by town
ZN: proportion of residential land zoned for lots over 25,000 sq. ft.
INDUS: proportion of non-retail business acres per town
CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
NOX: nitric oxides concentration (parts per 10 million)
RM: average number of rooms per dwelling
AGE: proportion of owner-occupied units built before 1940
DIS: weighted distances to five Boston employment centers
RAD: index of accessibility to radial highways
TAX: full-value property-tax rate per 10,000 Dollars
PTRATIO: pupil-teacher ratio by town
B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT: % lower status of the population
MEDV: Median value of owner-occupied homes in $1000's

Regression Model Performance Analysis

**Project Overview**
This project involves the application of various regression models to a dataset to predict the target variable. The goal is to evaluate and compare the performance of different algorithms based on key metrics like R-squared, RMSE, and MAE.

**Models Used**
Linear Regression
Ridge Regression
Lasso Regression
ElasticNet
ExtraTree Regressor
Gradient Boosting Regressor
K-Neighbors Regressor
XGBoost Regressor

**Key Findings**
**Top Performing Models:**

The GradientBoostingRegressor emerged as the best model, explaining 70% of the variance (R-squared = 0.693) with the lowest RMSE (5.085) and MAE (2.85).
The XGBRegressor also performed strongly, explaining 63% of the variance with slightly higher RMSE (5.511)and MAE (3.10) than the Gradient Boosting model.

**Moderate Performance:**

Models like Ridge, LinearRegression, ElasticNet, and Lasso performed well, However, they had higher RMSE and MAE than the top-performing models.

**Weaker Models:**

The ExtraTreeRegressor and KNeighborsRegressor had lower R-squared values and higher RMSE and MAE, indicating weaker performance in predicting the target variable.

**Conclusion**
Based on the analysis, the GradientBoostingRegressor and XGBRegressor are recommended for use due to their superior performance across all metrics. Future work could focus on hyperparameter tuning, additional feature engineering, and exploring ensemble methods to further enhance model performance.

# House Price Forecasting
> Applied machine learning algorithms and compared R^2 score to find optimal tecnique.

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [CodeExample](#codeexample)

## General info
> The dataset consists of 7600 rows and 21 columns. In this project, I mainly applied Decision Tree Regressor and Linear Regression to build ML models. Additionally, I used Ensemble Learning to boost the performance.
* Data Description
* Data Preparation
* EDA
* Machine Learning Algorithms
  * Data Preprocessing
  * Bagging
  * Pasting
  * Adaboost
  * Gradient Boosting
* Conslusion Table
* Deep Learning Model

## Screenshots
![Example screenshot](https://user-images.githubusercontent.com/63559049/102727864-4eab8000-42dd-11eb-9cc3-c59512254852.png)


## Code Examples
```Python
gbr = GradientBoostingRegressor( learning_rate = 0.1, max_depth = 3, n_estimators = 600, random_state=0)
gbr.fit(X_train, y_train)
print('Training score(R^2): {:.3f}'.format(gbr.score(X_train, y_train)))
print('Testing score(R^2): {:.3f}'.format(gbr.score(X_test, y_test)))
```

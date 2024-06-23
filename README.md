# Preprocessing with Logistic Regression

## Introduction

I am going to practice scaling data prior to training a logistic regression model. Scaler instance must be fit to the training data prior to scaling both the training and testing sets.

## Steps

1. Load the dependencies and data.

2. Create the `X` set by dropping the `Churn` column.

3. Create the `y` set from the `Churn` column.

4. Split the data into training and testing sets, setting `random_state=1`.

5. Test the accuracy of the models that are trained using scaled data for both the `StandardScaler` and `MinMaxScaler` by performing the following actions for each method:

    * Create the scaler instance and fit it to the `X_train` data.

    * Scale the `X_train` data.

    * Scale the `X_test` data.

    * Create a `LogisticRegression()` model and fit it to the scaled `X_train_scaled` and `y_train` sets.

    * Check the accuracy score for both the scaled training and testing sets using `model.score()`.

6. Which scaler instance produces a better accuracy score on the scaled testing data?

## Reference

*Iranian Churn Dataset*. 2020. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset [2023, September 20]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))

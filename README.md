# Medical-Insurance-Cost-Prediction

This repository contains a machine learning model that predicts the insurance charges of a person based on several factors, such as age, gender, number of children, and BMI. The model uses a dataset of insurance charges to train and make predictions.

## Dataset

The dataset used in this project is the [Insurance Cost Dataset](https://www.kaggle.com/mirichoi0218/insurance) from Kaggle. It contains 1338 rows and 7 columns, including the insurance charges and the factors that influence them.

## Preprocessing

The following steps were taken:

- Removed duplicates and missing values
- Encoded categorical features
- Scaled numerical features using StandardScaler
- Transformed the target column using log transformation to improve model efficiency

## Model Selection

Three different models were used to predict the insurance charges:

- Linear Regression
- Lasso Regression
- Random Forest

Random Forest gave the best result with an R^2 score of 0.82

## Conclusion

This project demonstrates how to use machine learning to predict insurance charges based on several factors. By preprocessing the data and selecting the right model, we can achieve a high level of accuracy in our predictions. Feel free to use this project as a starting point for your own insurance charge prediction model.

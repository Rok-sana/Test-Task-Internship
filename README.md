# Task3
Task description

You have a dataset (internship_train.csv) that contains 53 anonymized features and a target column. Your task is to build model that predicts a target based on the proposed features. Please provide predictions for internship_hidden_test.csv file. Target metric is RMSE. The main goal is to provide github repository that contains:

jupyter notebook with analysis;
code for modeling (Python 3);
file with model predictions;
readme file;
requirements.txt file.


Task was completed in Google colab

Solution

Because of non-linear elationships between the features and the target variable we can try to apply tree-boosted algorithm such as XGBoost. XGBClassifier can capture non-linear relationships between the features and the target variable, even when there is no correlation between the features. Also XGBClassifier is robust to outliers and noisy data, which can be present even when there is no correlation between the features. It can still find patterns in the data and make accurate predictions.

This  RMSE error : 0.000.

Recommendation to apply to the model  GridSearchCV or RandomSearchCV in the future.



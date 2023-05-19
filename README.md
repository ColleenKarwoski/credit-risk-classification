# credit-risk-classification

## Overview of the Analysis

* The purpose of the analysis is to build a model that can identify the creditworthiness of the borrowers. 
* A dataset of historical lending activity from a peer to peer lending services company was used. The data set contained dependent variables of loan size, interest rate, borrower income, debt to income ration, number of accounts, derogatory marks and total debt (X). It also contained the dependent variable, "loan status" (y). A value of 0 in the loan status column means the loan is healthy. A value of 1 means the loan is at a high risk of defaulting. 
* For this analysis, the data was split into training and test sent. A logistic regression model was fit using the training data(X_train and y_train) and predictions were made. 
* The model's performance was evaluated using an accuracy score, confusion matrix, and classification report.

## Results

* The logistic regression model has a high accuracy score of 0.99. 
* The precision score is high when predicting healthy loans with a score of 1.00, indicating a high accuracy of positive predictions. 
* The model as a precision score of 0.85 when predicting high risk loans, indicating reasonable accuracy when predicting high risk loans. 
* The model has a recall score of .99 for healthy loans and 0.91 for at risk loans indicating strong completeness of positive preditions in both instances.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Analysis indicates that the data can be used to train a Machine Learning Classification Model to predict creditworthiness of borrowers.
* The dataset is imbalanced, with significantly more healthy loans than at risk loans. It may be helpful to continue analysis on a resampled dataset.
* It is important that the model be able to accurately predict both 1's and 0's.


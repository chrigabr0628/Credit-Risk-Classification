# Credit-Risk-Classification

## Overview of the Analysis

The purpose of this analysis was to identify the creditworthiness of borrowers. The financial information of this dataset was on loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. The goal was to predict both the 0 (healthy loan) and 1 (high-risk loan) labels. In total, there were 75,036 healthy loans and 2,500 high risk loans.

The follwing steps were:
split the data into training and testing datasets by using train_test_split.
fit a logistic regression model by using the training data (X_train and y_train).
save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
evaluate the model’s performance by generating a confusion matrix and printing the classification report.

I utilized methods such as LogisticRegression, train_test_split, confusion_matrix, classification_report, etc. to collect the necessary data.



## Results

    * Accuracy: 99%

    * Precision: 100% for low-risk loans, 85% for high-risk loans, 92% on average

    * Recall: 99% for low-risk loans, 91% for high-risk loans, 95% on average



## Summary

The logistic regression model performs best as it predicted 100% for the healthy loans. However, it would seem wise to utilize a different model (if applicable) for high-risk loans or at least take caution with utilizing a logistic regression model for higher risk loans as it appears that it favors prediction of healthy loans.


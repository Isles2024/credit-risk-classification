# credit-risk-classification

## Overview of the Analysis

The purpose of this analysis is to predict the potential classification borrowers will be placed into (healthy loan vs high risk loan) by training and evaluating a model using lending data. The datset contained information on customers income, total debt and debt to income ratio, number of accounts, deragatory marks on their credit, and more. Using this data the goal was to predict wheather or not each customer would be a healthy loan or a high-risk loan for the bank. 

The analysis started with preprocessing the data into train and test clusters. Next came training the model and using logistic regression to fit the model with the trained data. Once the model was trained, fitted, and validated, it was evalauted using a confusion matrix and classification report to determine its final accuracy. 

## Results

Classification Report for healthy loans:
    * Precision = 1.00
    * Recall = 1.00
    * F1-Score = 1.00
    * Support = 56271

Classification Report for High-Risk Loans:
    * Precision = 0.86
    * Recall = 0.90
    * F1-Score = 0.88
    * Support = 1881

  Macro Average:
    * Precision = 0.93
    * Recall = 0.95
    * F1-Score = 0.94
    * Support = 58152

  Weighted Average:
    * Precision = 0.99
    * Recall = 0.99
    * F1-Score = 0.99
    * Support = 58152

  Accuracy:
     * F1-Score = 0.99
     * Support = 58152

## Summary

In conclusion, I'd reccomend for the bank to use the model. Even though it was more accurate in predicting healthy loan candidates vs high risk candidates, the overall weighted average of the model was classified at 99%, which is why I would recommend the bank use this model when classifying candidates for loans.


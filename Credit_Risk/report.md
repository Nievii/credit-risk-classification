## Module 12 Report 

## Overview of the Analysis

The aim of this study was to predict credit risk by applying machine learning methods, particularly logistic regression. 
Determining whether a loan is likely to be a healthy loan or one that is at high risk of default was the primary goal. Financial organisations can make better loan decisions by forecasting this.

Financial parameters including loan amount, interest rate, borrower income, debt-to-income ratio, number of accounts, negative marks, and total debt are included in the dataset. The loan_status target variable shows if a loan is at high risk (1) or healthy (0).

The distribution of healthy versus high-risk loans was revealed by a preliminary examination of the loan_status using value_counts. But accurate calculations will need real data for a thorough comprehension.

After reading the data and dividing it into training and test sets, a logistic regression model was created and fitted to the training set. The test set was then used to assess the model's performance.

Logistic regression was the main model employed in this investigation. The balanced accuracy score, confusion matrix, and categorization report are additional metrics that are included in the evaluation process.

## Results

Machine Learning Model 1:

Accuracy: 99%
Precision (Label 0 - Healthy Loan): 100%
Precision (Label 1 - High-Risk Loan): 85%
Recall (Label 0): 99%
Recall (Label 1): 91%
Machine Learning Model 2:

Accuracy: 99%
Precision (Label 0): 99%
Precision (Label 1): 99%
Recall (Label 0): 99%
Recall (Label 1): 99%

## Summary

Both machine learning models perform exceptionally well, attaining balanced precision and recall scores as well as excellent accuracy.

Model 1: Predicts loans with good health with high accuracy, but loans with high risk have slightly less accuracy. High recall for sound loans serves as a counterbalance to this.

Model 2: Exhibits consistent high performance for both healthy and high-risk loans, with balanced precision and recall.

Suggestion:
It is suggested that the corporation utilise Model 2, given its balanced predictions and overall great performance. The ultimate decision should, however, take into account the company's risk tolerance as well as the particular business requirements and the relative importance of recall and precision.

Evaluation of Performance: Model 2 regularly outperforms the other models in every metric.
Whether it is more important to correctly predict healthy loans (Label 0) or identify high-risk loans (Label 1) may determine the decision for the company.
In conclusion, Model 2 should be implemented; however, careful assessment of business priorities is suggested.

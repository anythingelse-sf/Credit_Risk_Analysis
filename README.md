 Credit_Risk_Analysis

## Overview of the Analysis: 
In this model we are analyzing a portfolio of loans, attempting to identify healthy loans and hihg-risk loans. We split the Data into Training and Testing Sets, create a Logistic Regression Model with the Original Data, and Predict a Logistic Regression Model with Resampled Training Data.

## The Results: 

### Logisitic Regression Model with Original Data
Accuracy Score: 99.14

Precision (Healthy Loans [0]): 1.00
Precesion (High Risk Loans [1]):0.85

Recall (Health Loans [0]): 1.00
Recall (High Risk Loans [1]): 0.88


## Logistic Regression Model with Resampled Training Data
Accuracy Score: 99.47

Precision (Healthy Loans [0]): 0.99
Precesion (High Risk Loans [1]): 0.99

Recall (Health Loans [0]): 0.99
Recall (High Risk Loans [1]): 0.99


## Executive summary: 

When examining the results of the data it would be defendable to say we can use the original logisitcal regression model and move on. The numbers are very good for healthy loans especially, and one could argue that the margin for error is acceptable. However, the model fails to accurately predict high-risk loans, which are more important to identify, making furhter analysis necessary to build a working model. 

The resampled training data brings all accuracy and prescision scores up over 99% and the model is adequate in its purpose.
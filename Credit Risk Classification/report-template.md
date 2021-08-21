# Module 12 Report Template

## Overview of the Analysis

The purpose of this application is to use resampling to create a model that can identify healthy loans vs high-risk loans.

The financial information that we looked at to create our model was based on loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. Looking at all this information we can then identify whether the loan is a healthy loan or high-risk loan. 

The value counts of our original data were 75,036 healthy loans and 2,500 high-risk loans. To make an analysis of the data we had to use the machine learning process of creating a model, fitting the data, and then making predictions. 

By doing all this we can make an evaluation of the data. The methods used in our evaluation were logistic regression and resampling using the oversampling method.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy = 95.20%
  
  * Precision (healthy loan)= 100%
  * Recall scores (healthy loan)= 99%
  
  * Precision (high-risk loan)= 85%
  * Recall scores (high-risk loan)= 91%




* Machine Learning Model 2:
  * Accuracy = 99.37%
  
  * Precision (healthy loan)= 100%
  * Recall scores (healthy loan)= 99%

  * Precision (high-risk loan)= 84%
  * Recall scores (high-risk loan)= 99%


## Summary

Both the models have a good balance accuracy score, Model 1 with 95.2% and Model 2 with 99.37%. After resampling the data, Model 2 performed slightly better than Model 1. 

If your goal is to accurately identify high-risk loans, I recommend you use Model 2. If you want to accurately identify healthy loans, either model will work.

Because financial institutions want to identify borrowers with high-risk (to reduce their liability of taking on high-risk loans) I recommend Model 2 for financial institutions. 
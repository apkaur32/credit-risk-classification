# Module 20: Credit-risk-classification

## Overview of the Analysis

* The purpose of this analysis was to use various techniques to train and evaluate a model based on loan risk. I used a dataset of lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* The data was based on seven financial factors: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt as predictive factors for the 'loan_status'. 

* As part of the analysis, I went through the following stages of the machine learning process:
1) Separating the data into labels and features by identifying the target variable first;
2) Spliting the data into training and testing datasets by using train_test_split;
3) Fitting the logistic regression model using training data;
4) Predicting for testing data;
5) Evaluating the model's performance using a confusion matrix and classification report. 


## Results

* Machine Learning Model 1: Logistic Regression Model with the Original Data
    * "(0) healthy loan" scores: 
    * Accuracy: 99%
    * Precision: 100%   
    * Recall: 100%   

    * "(1) high-risk loan" scores: 
    * Accuracy:  99% 
    * Precision: 87% 
    * Recall: 89%  

## Summary

* The model predicts both the healthy and high-risk loans quite well. The '0' (healthy loans) are predicted with 100% precision, 100% recall, and 100% f1-score which indicates the model forecasts all instances of healthy loans correctly and with utmost accuracy. The '1' (high-risk loans) have slightly lower scores, but the model is still accurate in forecasting that 87% of all instances are indeed high-risk when assessing '1' (high-risk loans) and classifies them correctly in 89% of the cases.
* The number of correct predictions is also much higher: (TN) 18679 for class '0' and (TP) 558 for class '1' than their FP/FN counterparts; indicating a reliable model. 
* Based on this model's positive performance, I recommended its use for being able to distinguish between the two loan statuses effectively and highlighting the creditworthiness of borrowers.






# Credit Risk Classification
Module 20 Challenge Files

## Overview of the Analysis

 The purpose of this analysis is to determine the effectiveness of the model. This model attempts to predict the creditworthiness of a loan. The dataset used to train this model includes financial information such as loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The customer's history, recorded as the loan outcome, was used as the target value. 
 
 First, the data is separated into the target variable (the loan status plotted as 'y') and the remaining columns as 'X'. The dataset is then split into training and testing groups. These were loaded into the model-fit-predict method, and a logistic regression was created. 

The Logistic Regression model uses training data to predict the outcome. The training outcomes are compared to the testing outcomes to determine the effectiveness of the model.  

## Results

The Logistic Regression model uses loan outcome recorded as '0' for a healthy loan and '1' for a high-risk loan as the target value. The model has an overall Accuracy score of 0.92 (92%), indicating that the model has a high likelihood of predicting an accurate outcome. 

**Healthy loans**
 - **Precision** 1.00 (100%) - means this model is excellent at predicting healthy loans. 
 - **Recall** 0.99 (99%) - indicates this model correctly identified almost all of the healthy loans. 

**High-Risk loans**
 - **Precision** 0.84 (84%) - This means 84% of the loans were correctly predicted as high-risk.
 - **Recall** 0.94 (94%) - of the identified high-risk loans were correctly labeled. 


## Summary

The Logistic Regression model is excellent at predicting healthy loans. The high **Precision** and **Recall** results of healthy loans show this model's effectiveness. However, many high-risk loans were missed. This could result in lost revenue for the customer if they rely on the model and take on more high-risk loans than expected, especially if those loans are large. 

The customer should carefully assess their risk tolerance before implementing this model, particularly if their goal is to identify risky loans. 
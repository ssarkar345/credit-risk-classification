# Module 12 Report

## Overview of the Analysis

The goal of this analysis is to assess the efficacy of a logistic regression model in forecasting the credit risk associated with various loans. Utilizing a dataset that encompasses financial details such as loan sizes, interest rates, borrower incomes, debt-to-income ratios, number of accounts, derogatory marks, and total debt, the aim is to predict whether a loan will be classified as a healthy loan ('0') or a high-risk loan ('1'). By evaluating the performance of this model, I was able to provide insights into its accuracy and reliability in identifying potential credit risks.

## Results

* Model 1: Logistic Regression
Accuracy: The model achieves an accuracy of 99%, indicating that it correctly classifies 99% of the instances.

Precision:

* Healthy Loans (Class '0'): The model has a precision of 1.00, signifying that it perfectly identifies true positives with no false positives.
* High-Risk Loans (Class '1'): The model's precision is 0.87, indicating moderate effectiveness in identifying high-risk loans, with some false positives.

Recall:

* Healthy Loans (Class '0'): The model has a recall of 1.00, meaning it perfectly identifies all instances of healthy loans with no false negatives.
* High-Risk Loans (Class '1'): The recall is 0.89, reflecting moderate effectiveness in identifying high-risk loans, with some false negatives.

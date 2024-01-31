
# Credit Card Default Prediction

## Project Overview
This project aims to predict credit card defaults, helping financial institutions minimize losses while supporting consumers to manage their debt more effectively. By leveraging historical credit data, the project develops a predictive model to identify individuals at risk of defaulting on their credit card payments.

## Problem Statement
Predicting credit card defaults is crucial for both lenders and borrowers. For lenders, it helps in mitigating financial risks and for borrowers, in avoiding debt traps. The goal of this project is to accurately forecast the likelihood of default, enabling proactive management of credit risks.

## Description
The objective is to develop a predictive model that accurately identifies individuals at risk of defaulting on their credit card payments. This tool will aid in proactive risk management and enhance decision-making processes related to credit issuance and management.


## Source Data
https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

## Data Exploration and Analysis
The dataset includes demographic information, credit data, and historical payment records of clients from a financial institution. Initial analysis focused on cleaning the data, handling missing values, and exploring the distribution and relationships of variables.

## Feature Engineering and Selection
We enhanced the dataset with engineered features such as average payment status and late payment counts to capture trends in payment behavior. Selection of relevant features was based on their correlation with the default event and their importance as determined by preliminary model evaluations.

## Model Development and Validation
Several machine learning models were experimented with, including Logistic Regression, Random Forest, and Gradient Boosting. The models were evaluated based on accuracy, precision, recall, F1 score, and ROC AUC. Gradient Boosting emerged as the most promising model, further validated through cross-validation techniques.

## Insights and Findings
Key insights from the analysis and modeling were documented, highlighting significant predictors of default and patterns discovered in the data.


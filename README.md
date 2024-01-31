
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

## Data Summary
The dataset comprises information on 30,000 credit card clients, including demographic details (age, sex, education, marriage status), credit amount, historical payment records, and bill statements over six months. Key features include:
- `LIMIT_BAL`: The amount of given credit.
- `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`: Demographic information.
- `PAY_0` to `PAY_6`: Repayment status for September 2005 to April 2005, respectively.
- `BILL_AMT1` to `BILL_AMT6`: Bill statement amount from September 2005 to April 2005.
- `PAY_AMT1` to `PAY_AMT6`: Amount of previous payment from September 2005 to April 2005.
- `default payment next month`: The target variable, indicating if the client defaulted the following month (1=yes, 0=no).

The data was cleaned to address missing values and outliers, ensuring a robust foundation for analysis and modeling.


## Feature Engineering and Selection
We enhanced the dataset with engineered features such as average payment status and late payment counts to capture trends in payment behavior. Selection of relevant features was based on their correlation with the default event and their importance as determined by preliminary model evaluations.

## Model Development and Validation
Several machine learning models were experimented with, including Logistic Regression, Random Forest, and Gradient Boosting. The models were evaluated based on accuracy, precision, recall, F1 score, and ROC AUC. Gradient Boosting emerged as the most promising model, further validated through cross-validation techniques.

## Algorithms Used
To predict credit card defaults, we experimented with several machine learning algorithms, comparing their performance based on metrics such as accuracy, precision, recall, F1-score, and AUC-ROC. The algorithms include:

- **Logistic Regression:** A baseline model for binary classification problems, providing a probabilistic understanding of class memberships.

- **Random Forest:** An ensemble learning method that operates by constructing multiple decision trees during training time to improve predictive accuracy and control over-fitting.

- **Gradient Boosting:** An ensemble technique that builds trees one at a time, where each new tree helps to correct errors made by previously trained trees. Gradient Boosting showed the most promise based on evaluation metrics and was selected for further tuning and validation.

Each model was trained on the dataset, and its performance was evaluated to determine the most effective algorithm for predicting credit card defaults.

## Conclusion
The project's aim to predict credit card defaults was approached through comprehensive data analysis, feature engineering, and experimenting with various machine learning models. Gradient Boosting emerged as the most effective model, demonstrating a balance between accuracy and the ability to generalize across unseen data.

Key insights revealed the importance of recent payment behavior and credit utilization as significant predictors of default risk. The project underscores the potential of machine learning in enhancing credit risk management strategies, enabling proactive measures to mitigate default risks.

Future work can explore more sophisticated models, deeper feature engineering, and alternative data sources to further refine predictions and uncover additional insights into credit card default behavior.

The provided Tableau dashboard offers an interactive platform for visualizing the data and model predictions, making the insights accessible to both technical and non-technical audiences.

This project illustrates the power of data science in financial risk management and provides a foundation for further exploration and development in the field of credit risk analysis.


## Insights and Findings
Key insights from the analysis and modeling were documented, highlighting significant predictors of default and patterns discovered in the data.


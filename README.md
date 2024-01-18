# Capstone-Project
Predictive Analytics for Credit Risk Assessment in Consumer Banking

# Description
This project aims to leverage predictive analytics for credit risk assessment, which is a critical function in consumer banking. By analyzing historical loan data, the project seeks to build a predictive model that can assess the risk associated with loan applicants. This model would help in making informed lending decisions, thereby reducing the risk of defaults and improving financial stability.

# Source Data
https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

# Sample Data
![image](https://github.com/TyShuro/Capstone-Project/assets/115968439/3fc2996d-7a62-4a47-870f-fe1c1dda485f)

# Content & Explanation
I have two tables to be merged by ID:

application_record.csv		
Feature name	Explanation	Remarks
ID	Client number	
CODE_GENDER	Gender	
FLAG_OWN_CAR	Is there a car	
FLAG_OWN_REALTY	Is there a property	
CNT_CHILDREN	Number of children	
AMT_INCOME_TOTAL	Annual income	
NAME_INCOME_TYPE	Income category	
NAME_EDUCATION_TYPE	Education level	
NAME_FAMILY_STATUS	Marital status	
NAME_HOUSING_TYPE	Way of living	
DAYS_BIRTH	Birthday	Count backwards from current day (0), -1 means yesterday
DAYS_EMPLOYED	Start date of employment	Count backwards from current day(0). If positive, it means the person currently unemployed.
FLAG_MOBIL	Is there a mobile phone	
FLAG_WORK_PHONE	Is there a work phone	
FLAG_PHONE	Is there a phone	
FLAG_EMAIL	Is there an email	
OCCUPATION_TYPE	Occupation	
CNT_FAM_MEMBERS	Family size	

credit_record.csv		
Feature name	Explanation	Remarks
ID	Client number	
MONTHS_BALANCE	Record month	The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on
STATUS	Status	0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days C: paid off that month X: No loan for the month

# Tasks / Ideas

Perform exploratory data analysis to identify key factors influencing credit card approvals.
Build a classification model to predict approval outcomes.
Use clustering techniques to segment applicants into distinct groups based on their financial profiles.

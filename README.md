## Executive Summary
Nowadays, there are many competitors coming out on market. It becomes important to hold customers. There must be many reasons to make customers leave the bank company. In this paper, I analyze what kind of customers are more likely to churn or not. For this analysis, I used a large database maintained by the bank company. This database contained relevant information of churn rate for bank customers at a specific time. I used a number of multivariate statistical techniques for our analysis.
I will create awareness about credit score, balance, tenure, possession of credit card, gender, and other factors leading to churn. I can suggest the company to focus on marketing, advertising, providing some options, and others to the customers who will churn in the future, which in turn will prevent the company loss of profit.

##Introduction
The bank company would like to notice which customers tend to leave. It is better for the bank company to prevent the customers leaving. Acquiring new customers cost more than retaining existing customers. I would like to suggest that we should focus on marketing on those who are likely to churn.
To figure out how to reduce the influence of churn, I would like to observe each factor which cause customer leaving the bank company. I will use predictive analytics with machine learning models to predict whether the customers churn or not.
Through exploratory analysis, data pre-processing, and creating machine learning models (Logistic Regression model, Decision Tree model, Random Forest model, and Support Vector Machine) utilizing R, the goal of my project is to uncover patterns that might be hidden in data and gain insight into possible predictors of churn.

## Dataset Overview Attribute:
   
o RowNumber o CustomerId o Surname
o CreditScore o Geography o Gender
o Age
o Tenure
o Balance
o NumOfProducts o HasCrCard
o IsActiveMember o EstimatedSalary
o Exited

## Data Description
I found this dataset from Kaggle.com. There is no additional source to explore. This dataset does not include many information. Especially, it does not show when they measure this for the given data. Regarding tenure, there is no information of year base or month base. I assume it is the year base tenure.
It has 14 columns and 10,000 observations from 3 countries (Spain, France, and Germany). There are 9 categorical variables and 5 numeric variables.

## Preprocessing Data
I reviewed the dataset to identify what attributes will be necessary to be used to analyze.
There is no missing value in this dataset. I removed the unnecessary attributes, RowNumber, CustomerId which is unique identifier for a given customer and Surname, which are not the important features to explain about who tends to leave the bank company from the dataset.
Also, I used a categorical variable for tenure instead of a numerical variable due to the explanatory power.
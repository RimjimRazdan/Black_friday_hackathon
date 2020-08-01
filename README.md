# Black_friday_hackathon

## Problem Statement/Objective:

This is Black Friday shopping dataset, from which a retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and purchase_amount.

Website: https://datahack.analyticsvidhya.com/contest/black-friday/

## Dataset Description

This dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand your feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem, the idea and dataset is taken from AnalyticsVidhya where the project is a part of a hackathon.

There are two datasets provided Train and Test; I will be using Train dataset for training using train-test split and the test dataset will be used as an input (set of independent variables) to predict the output (dependent variable -Purchase Amount)

* Shape of training set: (550068 records and 12 features)

* Shape of test set: (233599 records and 11 features)

### Various features:

1. User_ID : User ID
2. Product_ID : Product ID
3. Gender : Sex of User
4. Age : Age in bins
5. Occupation : Occupation (Masked)
6. City_Category : Category of the City (A,B,C)
7. Stay_In_Current_City_Years: Number of years stay in current city
8. Marital_Status: Marital Status
9. Product_Category_1: Product Category (Masked)
10. Product_Category_2 : Product may belongs to other category also (Masked)
11. Product_Category_3: Product may belongs to other category also (Masked)
12. Purchase : Purchase Amount (Target Variable)

## Process

I will try to clean the data set and explore different trends from the Black Friday shopping dataset. I will extract useful information that will answer questions such as: what gender shops more on Black Friday? Do the occupations of the people have any impact on sales? Which age group is the highest spender?

In the end, we will create a machine learning model that predicts the amount of money that a person is likely to spend on Black Friday depending on features such as gender, age, and occupation.

### The steps include: 

1. Data Wrangling (Pre processing data in python,Dealing missing values,Data formatting etc)
2. Exploratory Data Analysis (Descriptive statistics, Groupby, Correlation etc)
3. Model Development
4. Model Review and Evaluation

## Conclusion

Comparing the various models in the above steps, I concluded that the XGBRegressor model is the best model to be able to predict purchase amount from our dataset.

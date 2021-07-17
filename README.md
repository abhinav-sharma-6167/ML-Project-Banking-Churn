
# Bank Customer Churn Prediction
For a business in a stipulated period of time, customers can come under 3 major categories
 
1. Newly Acquired Customers
2. Existing Customers
3. Churned Customers

Customer churn/attrition is a tendency of customers to abandon a brand and stop being a paying client of a particular business.

Churned Customers means a direct loss of Marketing Acquisition Cost and possible revenue which could be capitalized post sale. Hence, predicting possible customers who can churn beforehand can help us save this loss. In order to retain them, they need to identify the customers as well as the reason of churning so that they can provide the customers with personalized offers and products. The aim of our project is to solve this problem for banking domain, by identifying which customers are at risk of churning and what are the reasons for churning with the help of supervised learning classification alogorithms.

# Data Set
In this project we are using a source of 10,000 bank records to predict the likelihood of a customer churn. You can  [click here ](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling) to get access to the raw data.

# Data Cleaning:
We removed unnecessary variables such as row number, customer names and IDs to make the dataframe more readable. Now, we are left with the below Columns:
* Age
* Balance
* CreditScore
* Estimated Salary
* Exited
* Geography
* Gender
* HasCrCard
* IsActiveMember
* NumberOfProducts
* Tenure

# EDA

![Churn by Geography](https://user-images.githubusercontent.com/44424472/126025672-7fc21789-9397-4d0d-9b30-ab5b07cd7ab7.PNG)

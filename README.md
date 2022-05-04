# Telecom Churn
> Build a machine learning model that is able to predict churning customers based on the features provided for their usage.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Business Recomendation](#Business-recomendation)
* [Acknowledgements](#acknowledgements)

## General Information
- In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

- For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

## Business Recomendation
- We have seen that the churn probability is more in cases when there is a huge difference in the recharge dates whether it be amount recharge or data recharge.

- To cope up with this, the telecom operator needs to roll out few exciting offers for high value customers so that they can be retained and these customers can recharge as per their favourite plans.

- Also, we can see that churn customers uses too many sachet plans in the month of August which indicates their short term retention in the current telecom operator.

- Since, the main business objective of this project is accuracy, we will be choosing a model which has high accuracy in both train and test set.

- No matter how the non-churn customers are predicted, the actual churn customers needs to be predicted correctly. Given that, the telecom operator will be rolling out offers to high risk customers, it won't be any big deal to roll out offers to wrongly predicted non-churn customers. In such cases, we need to ensure that recall is low.

- Again, if the company is running on losses, it can't roll out offers even for wrongly predicted non-churn customers.

- If business wants to maximize the correctness of actual churn customers, precision will be the best metric to go for. We can go with the model which gives high precision.

## Technologies Used
- pandas - version 1.2.4
- numpy - version 1.20.1
- seaborn - version 0.11.1
- matplotlib - version 3.3.4
- statsmodels.api - version 0.12.2
- sklearn - version 0.24.1

## Contact
Created by [@nehu7] - feel free to contact me!



# Azubian-Customer-Churn-Prediction-Challenge

![Alt text](<churn poster-1.png>)

Customer Churn Prediction for an African Telecommunications Company that offers airtime and mobile data bundles. The company wants to develop a machine learning model that can accurately predict the likelihood of each customer "churning" – becoming inactive and not making any transactions for 90 days.

## **What is Customer Churn?**
![Alt text](5-Effective-Tips-To-Reduce-Customer-Churn-removebg-preview-1.png)

Customer churn prediction refers to the process of using data analysis and predictive modeling techniques to identify customers who are likely to stop using a product or service. Churn, in this context, refers to customer attrition or the loss of customers from this African Telecommunications Company

## **Project Objective:**

The objective of this challenge is to develop a machine learning model to predict the likelihood of each customer “churning,” i.e. becoming inactive and not making any transactions for 90 days.

###**Hypothesis**

Null hypothesis(H0): There is no significant relationship between the customers' characteristics and the churn rate. In other words, the variables in the dataset have no impact on customer churn.

**Alternative hypothesisH1):** 

There is a significant relationship between the customers' characteristics and the churn rate. The variables in the dataset have an impact on customer churn.

**Business Questions****
1. What is the overall churn rate of the company?
2. Which region has the highest representation?
3. Which tenure has the highest representation?
4. Does the length of tenure (months) affect the churn rate of customers?
5. Which Region has most clients churning?
6. Do client churn or not churn if active for 90 days (Regularity)?
7. What's the correlation between the various features?

### **Project Process**

![Alt text](c1-1.png)

### **Getting our Data**

![Alt text](Z1-1.png)

The data was dowloaded from Zindi as a challenge.

To understand the data, we went through the variable definitions of the given columns which contains information related to telecommunications customers, including their region, tenure, recharge amount, frequency of recharge, revenue, data usage, and other variables.

### **Exploratory Data Analysis**

EDA (Exploratory Data Analysis) for this Project  involved analyzing and understanding the dataset to gain insights into the variables and their relationship with customer churn. It helped the team in identifying patterns, trends, anomalies, and correlations within the data, which informed feature selection, model building, and decision-making. Below are some visualizations of the EDA performed with a summary of insight gathered.

![Alt text](uni3-1.png) ![Alt text](uni1-1.png) ![Alt text](uni2-1.png) ![Alt text](bi3-1.png)

From the EDA performed we realized that the data is imbalanced since the number of customers who aren't churning made up the majority of the dataset.

In dealing with this issue:

1. All other evaluation metrics will be used except 'accuracy' since it will be in favour of the majority class

2. The type of machine learning algorithms that will be used are the Tree based models and other regression models.



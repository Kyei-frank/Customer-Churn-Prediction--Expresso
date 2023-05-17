# Customer-Churn-Prediction--Expresso

*Project Overview:*
In today’s commercial world, there is high competition and every customer is valuable. One of the biggest expenditures of any organization is customer churn. Customer churn also known as customer attrition or customer turnover is the percentage of customers that stopped using your company’s product or service within a specified timeframe. This projet is based on a Zindi challenge for an African telecommunications company(Expresso) that provides customers with airtime and mobile data bundles. The objective of this challenge is to develop a machine learning model to predict the likelihood of each customer “churning,” i.e. becoming inactive and not making any transactions for 90 days.

# Data Understanding
The train data consist of 1077024 rows and 19 columns, whiles the test data consist of 190063 rows and 18 columns. Each row represents the data of a unique customer. The difference between the train and test dataset is a column called CHURN that indicates if a client churned or did not churn. This is the target variable. There are 4 categorical variables(excluding the User Id column), and 13 Numerical variables.

## Variable Definition
- FREQUENCE: number of times the client has made an income
- TENURE: duration in the network
- FREQUENCE_RECH: number of times the customer refilled
- MONTANT: top-up amount
- DATA_VOLUME: number of connections
- ORANGE: call to orange
- ARPU_SEGMENT: income over 90 days / 3
- ON_NET : inter expresso call
- REGULARITY: number of times the client is active for 90 days
- TOP_PACK:	The most active packs
- FREQ_TOP_PACK: number of times client has activated the top pack packages
- REVENUE: monthly income of each client
- TIGO:	call to Tigo
- ZONE1: call to zones1
- ZONE2:	call to zones2
- MRG:	A client who is going
- REGION: The location of each client
- CHURN	variable: variable to predict - Target
    
## Author:
[FK Baffour](https://www.linkedin.com/in/frank-kyei-baffour-403b60100/)

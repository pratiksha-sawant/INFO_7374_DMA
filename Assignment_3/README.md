# Machine Learning and Marketing Analytics

## Report

https://codelabs-preview.appspot.com/?file_id=1_69ZjNUYdj2l1cHXMF6mnoencFInq1CGCmkLb5x4gEs#3

## Use Case 1 : Customer Attrition
### Machine Learning Models

•	Models like Logistic Regression, XgBoost and ensembling implemented to classify the whether the customer would remain active or inactive

•	Churn is indicated as boolean value True or False

•	Colab Links

    https://colab.research.google.com/drive/1yR-267MDawn-n3HErfkeaVNKoUZaSgcN

### ML as a service

Customer attrition predicted using AWS XGBoost algorithm on AWS Sagemaker which can be invoked by using REST APIs

ENDPOINT URL-
https://runtime.sagemaker.us-east-1.amazonaws.com/endpoints/xgboost-2019-08-02-23-47-26-992/invocations

API
INVOKE URL- https://hkc4x5lbmg.execute-api.us-east-1.amazonaws.com/churn-pred

---------------------------------------------------------------------------------------------------------------------------------
## Use Case 2 : Customer Lifetime Value Prediction
### Machine Learning Models

•	Models like Linear Regression and Randomforest Regressor implemented to predict the customer lifetime value

•	Colab Links

    https://colab.research.google.com/drive/1PQencEygm6MnsMJBIsfR9Q4XkQ0sEwky
    

### ML as a service

Customer Lifetime Value predicted using AWS XGBoost algorithm on AWS Sagemaker which can be invoked by using REST APIs

ENDPOINT URL-
https://runtime.sagemaker.us-east-1.amazonaws.com/endpoints/linear-learner-2019-08-03-02-30-27-302/invocations

API INVOKE URL-
https://jy0d7w6w48.execute-api.us-east-1.amazonaws.com/cltv

----------------------------------------------------------------------------------------
## Use Case 3 : Customer Segmentation

### Machine Learning Models

•	RFM Analysis implemented to identify the segments based on customer behavior by generating the rfm score of customers by calculating recency, frequency and monetary value 

•	Customer segments identified are listed below

    	Best Customer
    	Big Spenders
    	Loyal Customers
    	Almost Lost Customers
    	Lost and cheap customers
    	Average Customers

•	Models like KNN, Logistic Regression, RandomForest Classifier, SVM and Ensemble Modeling implemented to classify customers into different segments
 
 •	Colab links
 
    https://colab.research.google.com/drive/1WgOozirjDjqMMcdmrrcz40D19LKqE6I5#scrollTo=gXRcI5-BJ1f8
 
    https://colab.research.google.com/drive/12pdko4zvIR10zgwIdZQwkUyiT8fU0Q8i#scrollTo=_wliJzDXLqTU
 
### ML as a service

Customer segmentation performed using AWS algorithm on AWS Sagemaker which can be invoked by using REST APIs

arn:aws:sagemaker:us-east-1:673997752278:endpoint-config/customer-segmentation11

## Model Implementation

    https://colab.research.google.com/drive/1yR-267MDawn-n3HErfkeaVNKoUZaSgcN


# thyroidazure-cassandra
Thyroid disease a very common problem in India especially in female. Thyroid disorder can speed up or slow down the metabolism of the body. Hyperthyroidism and hypothyroidism are the most two common diseases caused by irregular functioning of thyroid gland.
 Machine learning plays an important role in predicting the thyroid disease. Machine learning algorithms helps in early detection of the disease and to improve the quality of the life. Different classification algorithms can forecasts the presence of the disease such as Logistic regression, Random Forest, Decision Tree, Naïve Bayes, Support Vector Machine, XG Boost, KNN.
 In the present work, the machine learning algorithms like logistic algorithm, Decision Trees, Random Forest, Support Vector Machine and XG Boost algorithm are used for classification of thyroid disease. Based on the obtained result Decision Trees algorithm is used to predict the thyroid disease. Web app is created to get data from users to predict the type of disease using flask. The user input and result is stored in Cassandra cloud database and the finally model is deployed on Azure cloud platform
# demo link
https://youtu.be/vELY7E19IJk
# Technical aspect
Python 3.9
Front-end: HTML, CSS
Back-end: Flask
IDE: Jupyter Notebook, PyCharm
Database: Cassandra
Deployment: Azure
# Workflow
#Data Collection
 The dataset is collected from the UCI repository page
 # Data Pre-processing
In this process, raw data is transformed into valid form for the machine learning models. This includes, data cleaning, imputing missing values using KNN imputers, removing outliers, drop unnecessary columns, imbalanced data set handling using random over sampler, encoding categorical columns etc.
# Data Modelling
Various classification algorithms like Logistic Regression, Decision Tree, Support Vector Machine and XG Boost are used. Hyper parameter tuning was also performed. Decision Tree and XG Boost algorithms were given better results. Decision tree model is finalized to predict the result
# Model evaluation
Model performance evaluated based on accuracy, confusion matrix, classification report. Multiple models were trained and evaluated based on accuracy score and recall. The best performing models were selected as final model. In our case, it is Decision tree and evaluation for the same is shown below 
 
# API Details or User Interface
Web app is created to get data from users to predict the type of disease using flask.
# Deployment
We will be deploying the model to AZURE.

 

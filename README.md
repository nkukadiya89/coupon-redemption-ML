# coupon-redemption-ML

                                           Recommendation system POC


# Installation Process

1) Download Anaconda distribution platform from https://www.anaconda.com/products/individual (Your data science toolkit).

2) Install and Run Anaconda distribution.
   
    For windows : Directly from start menu
    for Linux : Anaconda-navigator

3) Make a virtual Environment for your POC you can make it from Anaconda navigator.

4) Download all the needed libraries for your project in your working environment.

5) Open jupyter notebook.


# About the dataset
The following is a part of the description of the data:

1) ABC promotions are shared across various channels including email, notifications, etc. A number of these campaigns include      coupon discounts that are offered for a specific product/range of products. The retailer would like the ability to predict      whether customers redeem the coupons received across channels, which will enable the retailer’s marketing team to accurately    design coupon construct, and develop more precise and targeted marketing strategies.

2) The data available in this problem contains the following information, including the details of a sample of campaigns and        coupons used in previous campaigns 

                1) User Demographic Details
                2) Campaign and coupon Details
                3) Product details
                4) Previous transactions and more
                
3) Based on previous transaction & performance data from the last 18 campaigns, predict the probability for the next 10            campaigns in the test set for each coupon and customer combination,whether the customer will redeem the coupon or not?


# Working with POC

1) Data Understanding

    i) Reading of CSV file and understanding each
   ii) Check whattype of problem and datatype is there in data
    

2) Data Preparation

    i) After examinig all we need to prepare data for model purpose
   ii) This process include Mearging of tabels concatination of tabels and finding the aggrigation of data with tabels.
  iii) Finding the missing value and filling it is the most important step. 
  

3) Modeling Process
   
   i) After Data analysis done on each and every data we need to make a model or we can say that we need to apply the different       different algorithm on the train and test data to pridict data.
  ii) There are many algorithm in Machine learning. 
 iii) Broadly, there are 3 types of Machine Learning Algorithms
 
                                           1. Supervised Learning
How it works: This algorithm consist of a target / outcome variable (or dependent variable) which is to be predicted from a given set of predictors (independent variables). Using these set of variables, we generate a function that map inputs to desired outputs. The training process continues until the model achieves a desired level of accuracy on the training data. Examples of Supervised Learning: Regression, Decision Tree, Random Forest, KNN, Logistic Regression etc.

 

                                            2. Unsupervised Learning
How it works: In this algorithm, we do not have any target or outcome variable to predict / estimate. It is used for clustering population in different groups, which is widely used for segmenting customers in different groups for specific intervention. Examples of Unsupervised Learning: Apriori algorithm, K-means.

 

                                            3. Reinforcement Learning:
How it works: Using this algorithm, the machine is trained to make specific decisions. It works this way: the machine is exposed to an environment where it trains itself continually using trial and error. This machine learns from past experience and tries to capture the best possible knowledge to make accurate business decisions. Example of Reinforcement Learning: Markov Decision Process

                                    List of Common Machine Learning Algorithms
Here is the list of commonly used machine learning algorithms. These algorithms can be applied to almost any data problem:

 1) Linear Regression
 2) Logistic Regression
 3) Decision Tree
 4) SVM
 5) Naive Bayes
 6) kNN
 7) K-Means
 8) Random Forest
 9) Dimensionality Reduction Algorithms
 10) Gradient Boosting algorithms
 11) GBM
 12) XGBoost
 13) LightGBM
 14) CatBoost
 
 
 
4) Future direction and limitation

                                   What does Prediction mean in Machine Learning?
“Prediction” refers to the output of an algorithm after it has been trained on a historical dataset and applied to new data when forecasting the likelihood of a particular outcome, such as whether or not a customer will churn in 30 days. The algorithm will generate probable values for an unknown variable for each record in the new data, allowing the model builder to identify what that value will most likely be.

The word “prediction” can be misleading. In some cases, it really does mean that you are predicting a future outcome, such as when you’re using machine learning to determine the next best action in a marketing campaign. Other times, though, the “prediction” has to do with, for example, whether or not a transaction that already occurred was fraudulent. In that case, the transaction already happened, but you’re making an educated guess about whether or not it was legitimate, allowing you to take the appropriate action.

                                           Why are Predictions Important?
Machine learning model predictions allow businesses to make highly accurate guesses as to the likely outcomes of a question based on historical data, which can be about all kinds of things – customer churn likelihood, possible fraudulent activity, and more. These provide the business with insights that result in tangible business value. For example, if a model predicts a customer is likely to churn, the business can target them with specific communications and outreach that will prevent the loss of that customer.






























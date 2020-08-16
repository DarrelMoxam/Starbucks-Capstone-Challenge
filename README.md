
# Starbucks-Capstone-Project

[Udacity Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) 

# Installation 
Python
VsCode
Jupyter Notebook
Pandas
Numpy
Matplotlib
Anaconda
Seaborn
Json
Sklearn model selections
ProgressBar
Sklearn.metrics
Matplotlib patches
os
sys
Sklearn tree, Naive bayes, ensemble
itertools

# Project Motivation
This project part of my Data Science Nanodegree, and the objective is to try to find how Starbucks customers use the app, and how well is the current offers system. more importantly, to find patterns and show when and where to give specific offer to a specific customer. 

# The strategy for solving this problem is as follows:

Exploring and Visualizing the Data.
Pre-processing the data.
Applying Quick Data Analysis on the cleaned pre-processed data
Scaling the numerical features.
Trying several Supervised Learning Models.
Evaluating the models using the chosen metric (Accuracy) and then Choosing the best Supervised Learning Model among them.
If the results need to be improved, implementing GridSearchCV to find the best parameters (in order to improve the performance of the chosen model).
Analysis
This includes Exploring, Visualizing, and Analyzing data( Analysis will be performed after pre-processing to facilitate the flow of the project).
# File Descriptions
1. data:
      - Portfolio Data set:
This data set has 6 columns and 10 rows. The columns are as follows :
id (string): offer id.
offer_type (string): type of offer i.e. BOGO, discount, informational.
difficulty (int): minimum required spend to complete an offer.
reward (int): reward is given for completing an offer.
duration (int): time for the offer to be open, in days.
channels (list of strings): channels include mobile, web, email, and/or social.
      - Profile data set:
      This data set has 5 columns and 17,000 rows. The columns are as follows :
age (int) : age of the customer.
became_member_on (int) : date when customer created an app account.
gender (str) : gender of the customer (M : Male, F : Female, O : Others).
id (str) : customer id.
income (float) : customer’s income..
      - Transcript adata set:
 This data set has 4 columns and 306,534 rows. The columns are as follows :
event (str) : record description (i.e. transaction, offer received, offer viewed, etc.)
person (str) : customer id.
time (int) : time in hours since start of test.
value (dict of strings) : it can hold the values of ‘offer id’,’amount’,’reward’ and/or ‘difficulty’.
   

Medium BLOG post- https://medium.com/@mrmoxam/project-overview-8c4b42190383


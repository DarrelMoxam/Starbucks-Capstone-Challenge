
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

# Problem Statements
We will be exploring the Starbuck's Dataset which simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.
There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational. In a BOGO offer, a user needs to spend a certain amount to get a reward equal to that threshold amount. In a discount, a user gains a reward equal to a fraction of the amount spent. In an informational offer, there is no reward, but neither is there a required amount that the user is expected to spend. Offers can be delivered via multiple channels.
What is the proportion of clients who have completed the offers based on Gender?

2. What is the proportion of clients who have completed the offers based on their Age?
3. What is the proportion of clients who have completed the offers based on their Income Level?
4. What is the best performing model?
# Metrics 
I will use accuracy and F-score metrics for comparision and to test out the performance of the models.
Accuracy measures how well a model correctly predicts whether an offer is successful. However, if the percentage of successful or unsuccessful offers is very low, accuracy is not a good measure of model performance. For this situation, evaluating a models' precision and recall provides better insight to its performance. I chose the F1-score metric because it is "a weighted average of the precision and recall metrics".

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
   
   
Primary Questions for the project
 
#### 1. What is the proportion of clients who have completed the offers based on Gender?


#### 2. What is the proportion of clients who have completed the offers based on their Age?


#### 3. What is the proportion of clients who have completed the offers based on their Income Level?


### 4. What is the best performing model?
RandomForestClassifier works best with a final accuracy score on the testing data being 0.7947 and final F-score on the testing data: 0.6121


# Conclusion
In this project, we explored the Starbucks data set, analyzed, visualized to provide a solution to our queries along with creating 3 supervised machine learning models, and optimized the best one to answer our questions of interest. The model can be used to drive the necessary steps to decide on how to go about promoting offers to customers.

Medium BLOG post- https://medium.com/@mrmoxam/project-overview-8c4b42190383


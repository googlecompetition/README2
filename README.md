
# Problem Statement

The problem we are solving is using customer demographic and behavioural data to predict future customer revenue for Google Merchandise Store. The challenge for this problem is that we have the train set data from August 1st 2016 to April 30th 2018 and test set data from May 1st 2018 to October 15th 2018. However, we need to predict the revenue from December 1st 2018 to January 31st 2019, which has a 46 days gap from the training set. 

With the challenge we are facing, this problem has been divided into two parts: 1) which customer made the purchase from December 1st 2018 to January 31st 2019?   2) How much does each customer spend?

As the test set has 168 days window and 46 days gap to predict the next 62 days transactions, we created a master data set that has the similar data structure. Additionally, with more than 30 features in the dataset, we will use Light GBM model to train the dataset. More detailed process is listed as the followings. 

# Data Exploration and Visualization 


# Build Analytical dataset


# Statistical Result & Interpretation 



# Conclusion

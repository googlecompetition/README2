
# Problem Statement

The problem we are solving is using customer demographic and behavioural data to predict future customer revenue for Google Merchandise Store. The challenge for this problem is that we have the train set data from August 1st 2016 to April 30th 2018 and test set data from May 1st 2018 to October 15th 2018. However, we need to predict the revenue from December 1st 2018 to January 31st 2019, which has a 46 days gap from the training set. 

With the challenge we are facing, this problem has been divided into two parts: 1) which customer made the purchase from December 1st 2018 to January 31st 2019?   2) How much does each customer spend?

As the test set has 168 days window and 46 days gap to predict the next 62 days transactions, we created a master data set that has the similar data structure. Additionally, with more than 30 features in the dataset, we will use Light GBM model to train the dataset. More detailed process is listed as the followings. 

# Data Exploration and Visualization 
Data Visualization analysis is saved as the following Juptier Notebook
https://github.com/googlecompetition/Data-Visualization/blob/master/Google%20Analytics%20CRM%20.ipynb

# Build Analytical dataset
Our detailed modeling process is attached as RMD file as followings:
https://github.com/googlecompetition/Modeling/blob/master/Model_2

# Statistical Result & Interpretation 
Further Trails:
 1. Add more features on most frequent and standard divation for each factor
 2. Increase the number of training sets (Overlapping)
 3. Add time related features: Month and Year (Inflation and holiday reasons)

Coding attached as following:
https://github.com/googlecompetition/Modeling/blob/master/Model_2

# Conclusion
From this competition, what we learned:
 - New time series data methods 
   Design the training data set to the same time strcuture that predictive data has based on rolling sequence
 
 - The model might cause overfitting 
  Solutions: decrease the number of features using feature importance analysis, only select the important feature
  
  - Future approach like Netural Network might be useful 
 
From a business perspective 
 - Total revenue, sessions/webpages visited and time on sites for past several months do have a significant importance on future revenue 
 - City is also an important factor. Therefore, Google Merchdaise should advertise differently for each city, especially in ***
 
 
  

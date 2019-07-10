# default_bank
The loan_data data frame contains information on 3-year loans that were originated in 2013 by a local bank for customers 
residing in the United States. The company is looking to see if it can determine the factors that lead to loan default and 
whether it can predict if a customer will eventually default on their loan at time of loan origination. The goal is to 
become better at identifying customers at risk of defaulting on their loans to minimize the bank’s financial losses.  


The data set contains a mixture of applicant demographics (gender, age, residence, etc..), financial information (income, 
debt ratios, FICO scores, etc..), and applicant behavior (number of open accounts, historical engagement with the bank’s 
products, number of missed payments, etc. . . )  


Exploratory Data Analysis is conducted to examine the data and explore 
possible important variables. Variable Importance is determined by creating a Gini Index using the varImpPlot() function in 
Random Forest. After variables are selected, three different models are fit on the training data set including Random Forest, Decision Trees, and K-Nearest Neighbor. The models are then used on the test data set, and a recommendation is given to the bank through an 
analysis of F1 scores and false negative rates.

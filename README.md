# Creditcard_defaulter

#Project Title : Predicting whether a customer will default on his/her credit card

Problem Description
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

Data Description


Attribute Information:
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.


This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

In this project we have presented exploratory data analysis, visualization, classification model  with different types and interesting insights of the data based on the data. This dataset has around 30000 observations in it with 25 columns. Fundamental Analysis involves analyzing the  future profitability of a person whether he/she will default his/her credit card or not. Technical Analysis, on the other hand, includes reading the charts and using statistical figures to identify the limit balance , sex , eduction level , marital status and age of a defaulter. Our focus will be on the technical analysis part. We’ll be using a dataset of Taiwan credit card holder   for this particular project.
As a first step, we have loaded the data, we have mounted the drive. After mounting the drive, we have imported the important libraries such as numpy, pandas, seaborn, matplotlib and also all classification  model libraries with their metrics, which are useful for our analysis.

We have explored our data by checking all the necessary parameters like shape, head, tail, information of the columns and their data types and description of data like mean, min and max. We have performed exploratory data analysis, normalization, standardizing. 

Finally, we have fit the data using various supervised classification algorithms like Logistic Regression, DecisionTreeClassifier, Random Forest Classifier, KNeighborsClassifier, XGBClassifier ,  Support Vector Classifier, AdaBoostClassifier. These all in all three types of data i.e.: Given Data , Standardized Data and Normalized Data .   All the performance metrics of these models were compared against each other and the best model was used to predict the credit card defaulter and non-defaulter.


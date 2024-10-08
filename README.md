# data-science-toolkit
Summary of several data science models learned in MSBA-SA

## XGBoost
Class Workbook:  <br/>
https://rpubs.com/bscartz/xg-boost-toolkit <br/><br/>

Basic Description: <br/>
This is the most powerful and intricate tree-based model. It is an iterative process that learns based on the errors of previous iterations to arrive at final predictions. It can handle both classification and regression tasks. <br/><br/>

Usage: <br/>
This should be used when prioritizing accuracy over conveyability. <br/><br/>
Possible Use Cases: <br/>
Projections

## K-Means Clustering
Class Workbook: <br/>
https://rpubs.com/bscartz/kmeans-clustering-toolkit<br/><br/>

Basic Description: K-Means Clustering is an unsupervised machine learning algorithm used for partitioning data into clusters based on similarity. is used for clustering data points into groups, making it easier to understand patterns and relationships in the data. <br/><br/>


Usage: <br/>
This can be used when you want to define a set number of clusters (k). It can be more efficient than Hierarchical on large data sets.<br/><br/>


Possible Baseball Applications:
* Categorize different types of pitches based on various metrics
* Sort players into like groups


Possible Business Applications: 
* Compare customers to similar customers based on behavior and/or demographic data

## Hierarchical Clustering
Class Workbook:
Basic Description: 
Usage:
Possible Use Cases:

## Decision Trees
Class Workbook:<br/>

https://rpubs.com/bscartz/decision-trees<br/>

Included: boostrapping (imbalanced data)<br/><br/>


Basic Description: <br/>
Tree models are learning methods that split datasets based on the value of input features, arriving at stratified predictions based on numerous splits.
<br/><br/>
Usage: <br/>
This model can be used for both classification and regression tasks. It is particularly useful when the data has a mix of numerical and categorical features, and it helps visualize decisions in a straightforward way. It is more easily conveyed than the more complex tree-based models.
<br/><br/>
Possible Use Cases:

## LASSO Regression
Class Workbook: <br/>
https://rpubs.com/bscartz/lasso-regression<br/>
Included: missing data imputation (mice) <br/><br/>

Basic Description: <br/>
LASSO (Least Absolute Shrinkage and Selection Operator) Regression is a linear regression method that includes a penalty term to shrink some coefficients to exactly zero. <br/><br/>


Usage: <br/>
This model can be used when there is a very large number of variables, and many could be noise. This prevents overfitting. <br/><br/>


Possible Baseball Applications: 
* Predicting the time that a minor league player will spend in the minors based on a wide variety of possible predictors


Possible Business Applications: 
* Predicting house prices
* Identifying relevant features in economic forecasting

## Logistic Regression
Class Workbook:<br/>
https://rpubs.com/bscartz/log-regression<br/>
Included: predict(), confusion matrix, data partitioning <br/><br/>

Basic Description: <br/>
Logistic regression models the relationship between one or more independent explanatory variables and a dependent binary classification. <br/><br/>


Usage: <br/>
This model can be used whenever the response variable is a binary, such as 0/1 or yes/no. It can also be used to predict probability. <br/><br/>


Possible Baseball Applications:
* Predicting whether a team will win a game based on relevant statistics
* Predicting whether a baserunner will steal based on the situation.


Possible Business Applications:
* Predicting whether a customer will continue or cancel his subscription based on usage patterns
* Estimating the risk probability that a person or business will default on a loan.

## Linear Regression

Class Workbook: <br/>
[https://rpubs.com/bscartz/linear-regression](https://rpubs.com/bscartz/linear-regression-toolkit) <br/>
Included: log transform, interaction terms <br/><br/>


Basic Description: <br/>
Linear regression models the relationship between a dependent response variable and one or more independent explanatory variables. It fits a linear equation to the data. <br/><br/>


Usage: <br/>
This model can be used whenever observed variables have a linear relationship with the outcome variable. <br/><br/>


Possible Baseball Applications: 
* Predicting statistics based on other statistics when they are reasonably correlated.
  * Predict stolen bases based on top sprint speed.
* Assess the predictive performance of machine learning models.
  * Compare an xwOBA model to actual wOBA production. Does the xwOBA model over / undervalue any particular type of offensive production (power, speed, etc).


Possible Business Applications:
* Predict sales volume based on price










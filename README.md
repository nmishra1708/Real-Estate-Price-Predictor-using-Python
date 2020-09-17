# Project Report 

## Real Estate Price predictor using Python
Domain of project – Real Estate

## Problem Statement –
You are the Data Scientist at a real estate company. You have to analyse the data of your company, find insights and use the model for predicting house prices by given a set of features.

## Dataset - 
There are 14 attributes in each case of the dataset. They are:

#### CRIM - Its specify per capita crime rate by town
#### ZN - Its specify proportion of residential land zoned for lots over 25,000 sq.ft.
#### INDUS - Its specify proportion of non-retail business acres per town.
#### CHAS - Its specify Charles River dummy variable (1 if tract bounds river; 0 otherwise)
#### NOX - Its specify nitric oxides concentration (parts per 10 million)
#### RM - Its specify average number of rooms per dwelling
#### AGE - Its specify proportion of owner-occupied units built prior to 1940
#### DIS - Its specify weighted distances to five employment centers
#### RAD - Its specify index of accessibility to radial highways
#### TAX - Its specify full-value property-tax rate per $10,000
#### PTRATIO - Its specify pupil-teacher ratio by town
#### B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
#### LSTAT - % lower status of the population
#### MEDV - Its specify Median value of owner-occupied homes in $1000’s

## Implementation Details - 
In this project I will be walking you through analyzing the problem from collecting data, importing it to a Jupyter notebook, looking for promising attributes, finding out correlations, plotting graphs, creating a pipeline, dealing with missing values and much more. At the end we present the problem to the real estates company who will use the model for predicting house prices given a set of features.

## Results - 
+  For Hypothesis 1, The p-value is less than 0.05, confirming that that CHAS and MEDV are correlated. The estimate calculated shows, Median value of owner-occupied homes increases if the house’s tract bounds the river.
+  For Hypothesis 2, The p-value is less than 0.05, indicating that RAD and MEDV are correlated, but the estimate calculated shows, that median value of the owner owned homes decreases because of the radial highway accessability.
  +  The Linear Regression conducted to study the influence of various relevant factors on MEDV gives us following insights:
    +  CRIM(per capita crime by town), 
    +  NOX(Nitric oxide concentration), 
    +  DIS(weighted distance to five employment centers), 
    +  TAX(full-value property-tax per 10000 dollars), 
    +  PTRATIO(pupil-teacher ratio per town)  
    +  LSTAT(lower status of the population) have a negative effect on the MEDV.
    +  INDUS(proportion of non-retail businesses per town), 
    +  AGE(proportion of owner-occupied units built prior to 1940) doesn’t influence MEDV.
    +  ZN(proportion of residential land zoned for lots over 25,000 sq.ft.)  
    +  CHAS(Charles River Dummy Variable), 
    +  RM(Average rooms per dwelling), 
    +  RAD(index of accessibility to radial highways) influence MEDV positively.

# Project Name
> Surprise Housing Advance Regression

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below    their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* General Info
* Technologies Used
* Conclusions

## General Information
This project performs the exploratory data analysis on the housing dataset from Surprise housing. Prepares a linear regression model and checks the r2 score, RSS and RMSE. This project does regularization using Ridge and Lasso Regression and calculates the optimum value of Ridge and Lasso. It compares the r2 score, RSS and RMSE for Ridge and Lasso regression. It also compares the model coefficients for Ridge and Lasso regression and identifes to 10 predictor variable.


## Conclusions
* Optimal value of alpha for: Ridge = 1 and Lasso = 0.0001
* R2 score for train data for Ridge = 0.917469
* R2 score for test data for Ridge = 0.851355
* R2 score for train data for Lasso = 0.915108	
* R2 score for test data for Lasso = 0.849445
* Top 10 features are :
  - 1stFlrSF :First Floor square feet
  - 2ndFlrSF : Above grade (ground) living area square feet
  - OverallQual : Rates the overall material and finish of the house
  - SaleCondition_Normal : Condition of sale
  - Condition1_Norm : Proximity to various conditions
  - Neighborhood_Somerst : Physical locations within Ames city limits
  - BsmtFinSF1 : Rating of basement finished area
  - LotArea : Lot size in square feet
  - SaleType_New : Type of sale
  - OverallCond : Rates the overall condition of the house


## Technologies Used
* NumPy version: 1.21.5
* Pandas version: 1.4.2
* Seaborn version: 0.11.2
* Sklearn version: 1.1.2


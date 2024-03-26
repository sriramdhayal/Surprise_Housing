# House Pricing Assignment
> This assignment is a programming assignment wherein advanced linear regression model has to be built for the prediction of house price in Australia.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Model Results](#model_results)
* [Conclusion](#conclusion)
<br />

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market.
<br />

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of the new market.

Need to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
* Which variables are significant in predicting the price of a house.<br />
* How well those variables describe the price of a house.<br />
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Approach:
- Reading and Understanding the Data
- Visualising the Data
- Exploratory Data Analysis
- Data Preparation for Modelling
- Splitting the Data into Training and Testing Sets
- Rescaling the Features
- Building Ridge regression model with optimal value of Hyperparameter
- Making Predictions & Residual Analysis 
- Building Lasso regression model with optimal value of Hyperparameter
- Making Predictions & Residual Analysis 
- Comparison of Ridge and Lasso Models


## Technologies Used
- numpy - version 1.24.3
- pandas - version 2.0.3
- matplotlib - version 3.7.2
- seaborn - version 0.12.2
- sklearn - version 1.3.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Model Results
Ridge Regression: </br>
* R-squared 		 - Training Set: 0.940, Test Set: 0.918
* RMSE				 - Training Set: 0.095, Test Set: 0.112	
* No. of Features	 - 282

Lasso Regression: </br>
* R-squared 		 - Training Set: 0.924, Test Set: 0.919
* RMSE				 - Training Set: 0.108, Test Set: 0.112	
* No. of Features	 - 94

## Conclusion
Significant variables in predicting the price of house from Lasso Model are:
</br>
* GrLivArea - Above grade (ground) living area square feet
* TotalBsmtSF - Total square feet of basement area
* OverallQual_9 - Overall material and finish of the house is 'Excellent'
* OverallQual_10 - Overall material and finish of the house is 'Very Excellent'
* SaleType_New - Home just constructed and sold
* Neighborhood_Crawfor - location near to Crawford
* GarageCars - Size of garage in car capacity
* BsmtFinSF1 - Size of the basement finished area in square feet 
* OverallQual_8 - Overall material and finish of the house is 'Very Good'
* GarageArea - Size of garage in square feet


## Contact
Created by [@sriramdhayal] - feel free to contact me!

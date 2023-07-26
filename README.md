# HousePricePredictionAssignment
> Surprise Housing, a US-based housing company, is planning to enter the Australian market using data analytics to purchase houses below their actual values and flip them at a higher price. To aid in this decision-making process, a regression model with regularization was built to predict the actual value of prospective properties. The model helps identify significant variables that influence house prices and assesses how well these variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- With this model the company will be able to predict the prices.
- housing.csv was used in this project that contains all the housing data.


## Technologies Used
- pandas 1.4.4
- numpy 1.23.2
- seaborn 0.12.2
- matplotlib 3.5.3
- sklearn 1.1.2

## Conclusions
- GrLiveArea, OverallQual_VeryExcel, RoofMatl_WdShngl, OverallQual_Excel, Neighborhood_NoRidge, GarageCars, 2ndFlrSF are the significant predictors.
- We chose Lasso Regression model. The accuracy for train set is 89.78% and accuracy for test set is is 84.95%
- Alpha value for Ridge was 7.0 and for Lasso was 0.0001

## Contact
Created by [@philipfranklin] - feel free to contact me!

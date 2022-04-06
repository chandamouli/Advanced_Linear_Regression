# House price prediction - Advanced Linear regression
> Objective of this assignment is to predict house price using advanced regression techniques

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement :

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. 
The company wants to know:
  - Which variables are significant in predicting the price of a house, and
  - How well those variables describe the price of a house.

Business Goal:
To model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. Based on this data they can manipulate the strategy of the firm and concentrate on areas that will yield high returns. The model should help the management to understand the pricing dynamics of a new market.

Analytical Goals:
- A regression model using regularization in order to predict the actual value of the 
 prospective properties and decide whether to invest in them or not.
- Determine the optimal value of lambda for ridge and lasso regression. 
- Determine which variables are significant in predicting the price of a house and 
- Establish how well those variables describe the price of a house.

Data set used is train.csv available in this git

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Based on the final metrics displayed above for this data set, Lasso Regression performs better than Ridge and Linear regression models
- Also most of co-efficients are zero with Lasso model, hence it will be good where the model is
neither too simple nor too complex. Hence will address the issue of underfitting and overfitting.
- We will finalize Lasso regression as our preferred choice
- Optimal alpha value for Lasso is 0.01
- Top 5 features selected by Lasso are
  GrLivArea 0.327577
  OverallQual 0.186756
  Neighborhood_NridgHt 0.095961
  BsmtFinSF1 0.079385
  Neighborhood_Crawfor 0.076614

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.0
- numpy
- pandas
- seaborn
- sklearn
- statsmodels.api

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- References - Upgrad lesson content, Stackflow
- This project was based on Advanced Linear regression models like Lasso and Ridge


## Contact
Created by [@chandamouli] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
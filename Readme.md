# Lending Club Case Study
> The Goal is to predict the SalesPrice of houses in Australia for a US-Based companies so that they make decisions to buy and sell houses profitably . Also identify the top predictors so that the company can get an idea on the general trend.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information
- The assigment is about predicting house prices
- The model used to predict the target variable is regression model , the metric used to measure goodness of fit is r-squared
- Regularization techniques like Ridge and Lasso have been applied to reduce overfitting and make the model more generic and robust
- MinMax Scaler was used for scaling numerical data
- Backward Feature Selection was used 

## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.24.2
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- re - version 2.2.1
- Scikit-learn 1.1
- SciPy 1.11.3
- statsmodel 0.14.0



## Conclusions
- The 5 most important fetures to the model are '1stFlrSF', 'OverallQual', '2ndFlrSF', 'LotArea', 'OverallCond'
- The Ridge Scores are 1 . R2 Score of Ridge Training - 0.91 2 . R2 Score of Ridge Testing - 0.9
- The Lasso Scores are 1. R2 Score of Lasso Training - 0.9049 2. R2 Score of Lasso Testing - 0.9







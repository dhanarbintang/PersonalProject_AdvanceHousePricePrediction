# PersonalProject_AdvanceHousePricePrediction
A Personal Project of Property Price Prediction, In participation with kaggle House Price Prediction Competition :
(https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

This is a property price prediction using an XGBoost Regression Model.

The dataset used in this project is House Prices - Advanced Regression Techniques from : https://www.kaggle.com/c/house-prices-advanced-regression-techniques

In this project, I try building a XGBoost Regression Model to predict the final price of a house for the purpose of competing in a kaggle competition.
This project is done trough a number of iteration :

Iteration : 
 0. Base Feature : year and month of sale, lot square footage, and number of bedrooms
 1. Same Feature, Outlier & Data cleaning applied
 2. Added new feature : FullBath & HalfBath
 3. Added Categorical feature : MSZoning
 4. Changing Outlier removal group by to MSZoning
 5. Added Feature : OverallQual & OverallCond

This Project Result in an RMSE of 0.23200, which ranked in 4335.

# Predicting Internet Speed: An Analysis of Demographic Influences

## Summary
High speed internet connection or “broadband” is highly correlated with demographic
characteristics such as education level, income and race. Research by the U.S. Census Bureau
found that, counties with lower median household incomes (<$50,000) had household internet
subscription rates ten percentage points lower than counties with median household incomes of
$50,000 or more. We will implement a machine learning framework consisting of classification
models to predict broadband access using demographic data from the U.S census bureau and
internet speed data from OOkla at the county level. This analysis is particularly relevant as the
nation experiences an unprecedented shift to remote work and online learning.

## Data
The data used for this analysis is all publicly available and will come from two main sources:
* Speedtest by OOkla Global Fixed and Mobile Network Performance Map Tiles - provides global fixed broadband and mobile (cellular) network performance metrics.
* United States Census Bureau - releases demographic and economic data, which we will use to construct the features for our model.

## ML Approach
Using the speedtest data from OOkla we can determine whether counties have access to high speed internet or not. We trained our models to predict broadband access using demographic data from the counties that appear in the OOkla dataset. 
We implemented classification models like linear regression and support vector machines to make our predictions. We used k-fold Cross Validation to choose the best predictive model. Finally, we will predicted broadband access in counties where internet speed data is not available.




## ABSTRACT:
In this case study, we have been identified by Surprise Housing, a US based housing company which uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. The company wants to enter the Australian Market and hence are looking at prospective properties to buy. They want to understand what factors are affecting the prices and how exactly those factors are influencing it. The company would then manipulate the strategy of the firm and concentrate on areas that will yield a high return.

## OBJECTIVE: 
We need to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns and guide the company in making the best decision.

## INTRODUCTION:
A house is usually the single largest purchase an individual will make in their lifetime. Such significant purchase warrants being well-informed about what a house’s selling price should be; for the buyer, as well as the seller or real estate broker involved. Machine learning provides us with the tools we need to look at a large data set and spit out a predicted value, which was our main goal in this project. Using a dataset containing information on houses by different machine learning techniques to predict sale prices based on both practical intuition and those observed through our exploratory data analysis and model fitting processes:

### Ridge Regression: 
Ridge Regression is a technique for analyzing multiple regression data that suffer from multicollinearity. When multicollinearity occurs, least squares estimates are unbiased, but their variances are large so they may be far from the true value. By adding a degree of bias to the regression estimates, ridge regression reduces the standard errors. It is hoped that the net effect will be to give estimates that are more reliable. 

For ridge regression, we introduce GridSearchCV. This will allow us to automatically perform 5-fold cross-validation with a range of different regularization parameters to find the optimal value of alpha. 

### Lasso Regression: 
Lasso regression analysis is a shrinkage and variable selection method for linear regression models. The goal of lasso regression is to obtain the subset of predictors that minimizes prediction error for a quantitative response variable. The lasso does this by imposing a constraint on the model parameters that cause regression coefficients for some variables to shrink toward zero. Variables with a regression coefficient equal to zero after the shrinkage process are excluded from the model. Variables with nonzero regression coefficients variables are most strongly associated with the response variable. Explanatory variables can be either quantitative, categorical, or both. 

## METHODOLOGY: 
- Importing Dataset
- Data Cleaning
- Exploratory Data Analysis
- Data Preparation
- Building ML Model
- Evaluating the Model

  ## CONCLUSION:
  Regression	Alpha Value	  Train Score	  Test Score
  Ridge        	100	           0.81	         0.83
  Lasso       	0.01       	   0.9       	   0.88

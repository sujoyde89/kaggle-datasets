### This repository contains solution code and explanation for house-prices-advanced-regression-techniques problem of kaggle - https://www.kaggle.com/c/house-prices-advanced-regression-techniques
#### Problem statement  
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

The metric that the competition will use to evaluate our model is root mean squared error

#### Acknowledgments

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

#### Motivation
This is a playground competition where we can test our machine learning skills related to regression. This is problem containing 1460 train samples and 1459 test samples. So, it is a problem where we can iterate and test our skills very quickly

#### Dependencies
1. Python 3+
2. Pandas
3. Numpy
2. Sklearn
3. Matplotlib
4. Xgboost
7. Keras

#### Description
There are two files
1. House Prices Visualization - It has been used for visualization purposes. Explanation for the visualizations has not been given. the idea is to infer from the visualization and to modify the features in the House Prices Regression file
2. House Prices Regression - This is the main file. The approaches given below has been done:-  
  a) Oulier treatmet  
  b) Missing values imputation  
  c) Feature engineering  
  d) Feature selection  
  e) Producing a simple ensemble model  
  
  Algorithms used
  1) Ridge Regression- http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html  
  2) Lasso Regression- http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html  
  3) Xgboost- https://github.com/dmlc/xgboost  
  4) Random forest- http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html  
  5) Keras Regressor- https://keras.io/scikit-learn-api/

##### Final result
<i><b>Our final simple ensemble model is giving us a public leaderboard score of 0.11774 placing us in the top 17% in the competition as of 30th June 2017</b></i>

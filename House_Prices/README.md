# House Prices

This is a typical regression problem, there are lots of single regressor like, Lasso, Ridge Regression, ElasticNet, RandomForestRegressor,
GradientBoostingRegressor, SVR and etc.

Here I ensemble most of these regressors and train on emsemble model. Besides, there are also some important points like **meta model**.
Meta Model uses one of the regressor as the last layer. It uses KFfolds to leave one piece of data to be validated. The meta model uses
the predictions as input. 

The data preprocessing is also worth to mention.

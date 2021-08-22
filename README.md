# cancer-rate-reg
This repo contains solution to https://data.world/exercises/linear-regression-exercise-1.  
The goal is to predict cancer mortality rate through US county data. OLS and a few other Linear models have been implemented.  
The best performer is OLS. Refer to [this thread](https://stats.stackexchange.com/questions/410324/why-is-lasso-and-ridge-not-giving-better-results-than-ols) if that's surprising.  
Furthermore, two OLS are implemented, one from [sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) and one from [statsmodels](https://www.statsmodels.org/stable/generated/statsmodels.regression.linear_model.OLS.html). sklearn's OLS gives an R-square of 70% on out-of-sample data

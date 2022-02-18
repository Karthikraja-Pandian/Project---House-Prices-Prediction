## House Prices dataset: Feature Selection

In the above file, we will select a group of variables, the most predictive ones, to build our machine learning models. 

### Why do we need to select variables?

1. For production: Fewer variables mean smaller client input requirements (e.g. customers filling out a form on a website or mobile app), and hence less code for error handling. This reduces the chances of bugs.
2. For model performance: Fewer variables mean simpler, more interpretable, less over-fitted models


**We will select variables using the Lasso regression: Lasso has the property of setting the coefficient of non-informative variables to zero. This way we can identify those variables and remove them from our final models.**

# regression_model_selection

In this notebook, I built different linear regression models using `California Housing Data` fetched from `sklearn.datasets`:
- Linear regression (with normal equation and iterative optimization (SGD)), Polynomial Regression
- Regularizarized regression models - Ridge, Lasso, Elastinet
- I will be tuning polynomial degree, regularization rate and learning rate with hyper-parameter tuning and cross-validation.
- I will also do tuning via Grid Search and Randomized Search via `GridSearchCV` and `RandomizedSearchCV`.
- Lastly, I will be comparing different models in terms of their parameter vectors and mean absolute error on train, dev (validation) and test sets, and analyze their evaluation score on the test dataset.

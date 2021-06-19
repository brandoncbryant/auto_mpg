# ARCHIVED

# auto_mpg
The Jupyter notebook contains a regression analysis on the Auto MPG data set from the UCI repository. The dataset is imported into a pandas dataframe, the response undergoes a Box-Cox transformation, the predictors are centered and standardized, and then the regression is performed via a pipeline of PolynomialFeatures and RidgeCV. An r^2 score of ~0.8 is achieved and the residual plot confirms that the variability of the response data is well-explained by the model.

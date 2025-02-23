# dsei2100s23hw4p3-feature-selection

The diabetes dataset from sklearn is taken for a regression problem where 10 features are used to predict the progression of diabetes.The task here is to use multiple techniques of feature selection to try to interpret the strength of the features in the dataset. The following techniques are used:

- Pearson correlation coefficient using r_regression from sklearn (univariate feature selection)
- Mutual information using mutual_info_regression from sklearn (univariate feature selection)
- Random forest feature importance using RandomForestRegressor from sklearn (multivariate feature selection)
- Recursive feature elimination using sklearn.feature.selection.RFE with a Support Vector Regressor SVR (multivariate feature selection)

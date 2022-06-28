# Taha_portfolio
My Data science portfolio
# Project 1 : Crime and Communities : Prediction of crime rates in communities.
The dataset used for this study concerns crime according to the community in the US. This data it is prepared using real data from socio-economic data from 1990 US Census Law enforcement data from 1990 US LEMAS, and crime data from 1995 FBI UCR. This study involves the applications of six regression algorithms: Linear Regression, Random Forest Regression, Decision Tree Regression, Ridge Regression, Lasso Regression, Elastic Net regression.
* First, we describe the dataset and prepare it for the study. 
* Then we studied the multicollinearity between features and we used Principal Component Analysis (PCA) method and the Partial Least Square method (PLS) to reduce dimension (ie. features) and use it later in regression. 
* Finally, we applied penalized regression to solve the problem of multicollinearity, and then we repeated the study with the best features selected.

The evaluation of the model was an essential part of the process of this study to evaluate its performance and how well it is performing in its predictions. The basic concept of evaluating the performance of a model is to compare the original observations of the target variable with the predicted ones according to a specific metric. The metrics below are the ones used in this study to evaluate and compare the different models : MSE : Mean squared error. MAE : Mean absolute error. RMSE : Root squared mean error. R-squared : Coefficient of determination. The Cross-Validation method was applied too to estimate the skill of algorithms on unseen data and to have more accurate measures to compare between the different models.

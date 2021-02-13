# Stacking-to-Choose-the-Best-Possible-Algorithm

## Selection of the best algorithm
Stacking refers to a method of joining the machine learning models, similar to arranging a stack of plates at a restaurant. It combines the output of many models. The performance of stacking is usually close to the best model and sometimes it can outperform the prediction performance of each individual model

The objective is to get accurate predictions of the target variable, with the most relevant explanatory variables. We will do that by applying machine learning models such as Random Forest, Lasso regression, and Gradient Boosting.Then let us stack the output of these individual models and pass it to a ridge regressor to compute the final predictions. Stacking utilizes the strength of each individual model by using their output as input to the final model.

## Selection of the best features
In machine learning terminology, Least absolute shrinkage and selection operator (Lasso) is a regression analysis method that accomplishes both variable selection and regularization in order to enhance the prediction accuracy and interpretability of the model. It alters the model fitting process and selects only a subset of the covariates. It achieves this by forcing certain coefficients to be set to zero, and remove these coefficients in building the model.

Let's build the best model

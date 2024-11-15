In this project , we are using data from a European Bank. 

The objective is to create a Naive Bayes model that predicts whether a customer will churn with the help of the banking data.

Our target variable is `Exited`. This is a Boolean value that indicates whether or not a customer will churn or not( 0: not left, 1: left).

We are using Naive Bayes as it works well in classification tasks like this one where we are trying to predict on a binary class.There are several
different types of implementation of Naive Bayes algorithm in scikit-learn, and each assumes that all of the predictor variables are of a single type (ex: Gaussian for continuous variables, Bernoulli for binary variables, Categorical for categorical features and Multinomial for discrete features).

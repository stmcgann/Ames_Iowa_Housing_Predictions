# Ames_Iowa_Housing_Predictions
Used scikit-learn Linear Regression modeling techniques to predict housing prices in Ames, IA. (Kaggle Competition)

Using 4 Linear regression models, I predict housing prices for properties in Ames, IA. There are 80 features in the data set to predict housing price. 

Model 1 - Linear regression using 1 feature: Year Sold
Model 2 - Linear regression using only scaled, numerical features from the data set. Features were selected by using Lasso regularization. 
Model 3 - Linear regression using scaled, numerical features. Features were selected by using Elastic Net regularization. 
Model 4 - Linear regression using scaled, numerical features. Features were selected using a scikit-learn's VarianceThreshold method. VarianceThreshold was set to 0.50. 

All 4 sets of predictions were submitted to the Kaggle competiton. Through 4 sets of submissions, I improved my standing in the Leaderboard by 19 spots. 

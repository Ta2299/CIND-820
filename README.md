# CIND-820
Big Data Analytics Capstone Project

Logistic regression model
features were selected by looking at the correlation amongst the variables as well as performing Boruta analysis.
k-fold cross validation performed on the dataset where k = 10.
two logistic regression models were made: one with just the selected variables, the other with the selected variables + PCA.
logistic regression models were used to predict values.
confusion matrix was developed and analysis was done based on the CM.
find the most important variables.

Naive bayes model
normalization was done on the numeric data.
10-fold cross validation was used as the control method.
two models were created, one with PCA and one without.
the model was used to create a confusion matrix which was then used for analysis.
find the most important variables.

Decision tree model
use 10 fold cross validation on two different kinds of decision tree algorithms.
two types of decision trees were rpart and ctree.
build two models for each type of decision tree, one with PCA and one without.
Create a confusion matrix for each model for analysis.
find the most important variables.

Evaluate the best models of each type using precision, accuracy and other metrics

Contents: 
Data description file which was used for the bivariate/univariate data analysis.
Interim Report on the rice varieties and the analysis which will be done.
Initial results and code contains the regression model analysis.
There is also a csv. file of the dataset used. 
ctree1.png is an image of the ctree decision tree.
Ctree file for all the ctree analysis and code.
Decision Tree file contains all the rpart analysis and code.
Naive bayes file has all naive bayes analysis and code.
Feature selection and logistic regression file has the feature selection (boruta) and LR analysis and code.

Final Report contains all the analysis and conclusions drawn.


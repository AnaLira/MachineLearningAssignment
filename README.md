# MachineLearningAssignment
Coursera Machine Learning Assignment

This machine learning algorithm tries to predict the type of exercise (quality) performed by a  subject according to different body  measures taken by monitoring devices during the activity.  

The first step was to define the variables to use as predictors, for which different data cleansing and filtering steps were taken.

Afterwards, different training methods and configurations were tested until a model with high accuracy and low error rate was obtained. The resulting best model has the following characteristics:

1) Only numeric predictors, with no NAs and blank values were considered.
2) The method used was "gbm", with Accuracy metric, since the value we want to predict is a classification and not a continuos range.
3) The predicted value was changed to a numeric factor variable from 1 to 5 (instead of characters)
4) Cross validation with 10 fold and repeated 5 times

The final model had an Accuracy of 1, with and out of sample error rate of zero for the 95% confidence interval.


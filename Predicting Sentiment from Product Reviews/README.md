
## Predicting sentiment from product reviews
#### Data from Amazon.com to predict whether the sentiments about a product (from its reviews) are positive or negative.

##### Explore logistic regression and feature engineering with existing GraphLab functions.
    •	Use SFrames to do some feature engineering
    •	Train a logistic regression model to predict the sentiment of product reviews.
    •	Inspect the weights (coefficients) of a trained logistic regression model.
    •	Make a prediction (both class and probability) of sentiment for a new product review.
    •	Given the logistic regression weights, predictors and ground truth labels, write a function to compute the accuracy of the model.
    •	Inspect the coefficients of the logistic regression model and interpret their meanings.
    •	Compare multiple logistic regression models.
    •	Implement gradient ascent.
    •	Given a set of coefficients, predict sentiments.
    •	Compute classification accuracy for the logistic regression model.


 ##### Logistic Regression with L2 regularization
    •	Extract features from Amazon product reviews.
    •	Convert an SFrame into a NumPy array.
    •	Write a function to compute the derivative of log likelihood function with an L2 penalty with respect to a single coefficient.
    •	Implement gradient ascent with an L2 penalty.
    •	Empirically explore how the L2 penalty can ameliorate overfitting.


  ##### Exploring precision and recall
    •	Use Amazon review data in its entirety.
    •	Train a logistic regression model.
    •	Explore various evaluation metrics: accuracy, confusion matrix, precision, recall.
    •	Explore how various metrics can be combined to produce a cost of making an error.
    •	Explore precision and recall curves.

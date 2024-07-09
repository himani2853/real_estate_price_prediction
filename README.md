# Real_Estate_Prediction_Model

This project aims at predicting the price of a house as output by taking in certain inputs such as area type, location, size, society etc.

We begin by pre-processing the data by checking null values and missing values followed by removing them either by dropping or by replacing them with appropriate values. There is also proper handling of categorical encoding as we prefer only dealing with numbers.

We also use matplotlib for plotting the values of the given input for the data pre-processing.

Furthermore, we also gonna check for outliers in the data using "box plots" and then eventually removing them with the help of our code.

For the ML model, we started with Linear regression. But to make sure that this is appropriate model, we also applied GridSearchCV for Lasso Regression, Decision Tree and compared the best_score.

Finally, the project ends with training the model with Linear Regression model and predicting the price of test data.

# Class 2 Take-home exercise

This assignment uses data from Kaggle's [titanic](https://www.kaggle.com/c/titanic/data) competition. titanic.csv is in this repo, so no need to download from that website.

1. Read titanic.csv into a DataFrame
2. Define Pclass and Parch as the features, Survived as the response
3. Split the data into training and testing sets (use train/test split modules from sklearn)
4. Fit a logistic regression model and examine the coefficients to confirm that they make intuitive sense.
5. Create a confusion matrix and document the model's sensitivity and specificity. 
6. Add age as a feature, and calculate the testing accuracy. 

Remember to fit your model on the training data and run metrics on the test set.
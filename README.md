# Artificial Intelligence in Enterprise Systems
CLO-2: Write industry standard code and use git to work in agile environment for developing enterprise AI products  
CLO-6: Develop and deploy Enterprise AI solution pipeline using various technologies (i.e., Local,  Dockers, Heroku or cloud) 

**Linear Regression Model for Data Prediction**

This Python script demonstrates the use of linear regression to predict output values based on input features. Let’s break down the key components:

**Data Generation**
We create synthetic data for demonstration purposes.

X represents the input feature (a 1D array of 100 random values between 0 and 1).
y is the output (target) variable, generated as y = 2X + 1 with added random noise.
Model Initialization:

We create an instance of the LinearRegression class from the scikit-learn library.
This model will learn the linear relationship between X and y.
Model Fitting

The model is trained using the input feature (X) and corresponding output (y).
It learns the best-fit line that minimizes the prediction error.

**Making Predictions**

We generate test input data (X_test) evenly spaced between 0 and 1.
The trained model predicts output values (y_pred) for this test data.

**Visualization**
You can visualize the results by plotting the original data points (X, y) and the regression line (y_pred).



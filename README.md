# Linear-Regression-for-Prediction-of-Salary
The code defines a class called Linear_Regression that represents a simple linear regression model using gradient descent optimization.

INITIALIZATION:
->The constructor('__init__') takes two parameters:'learning_rate'(step size for updates') and 'no_iterations'(number of optimization iterations).

FITTING THE MODEL:
->The 'fit' method takes input data 'X'(features) and 'Y'(target values).
->Initializes weights('w') and ('b') as zeros.
->Performs gradient descent for the specified number of iterations.
->In each iterstion,it calls the 'update_weights' method to adjust the model parameters.

UPDATING WEIGHTS AND BIAS:
->The 'update_weights' method:
->Predicts 'Y' values ussing the current weights and bias.
->calculates gradients('dw' for weights,'db' for bias) based on prediction errors.
->updates the weights and bias using gradients and learning rate.

PREDICTION
->the predict method
->takes input features 'X'.
->Computes predictions by multiplying input features with learned weights and adding bias.

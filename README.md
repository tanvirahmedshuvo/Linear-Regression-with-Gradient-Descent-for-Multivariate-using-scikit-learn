# Linear-Regression-with-Gradient-Descent-for-Multivariate-using-scikit-learn

 
Dataset Preparation:

Created a small dataset with features (RAM(GB), ROM(GB), Display(inches)) and a target (Price($)).

Data Preprocessing:
Used StandardScaler to standardize features for better gradient descent performance.

Gradient Descent via SGDRegressor:
The SGDRegressor class is used for linear regression with stochastic gradient descent.

Model Evaluation:
Mean squared error is calculated to evaluate the model's accuracy.
Predictions are compared against the actual test data.

Plotting:
Actual vs Predicted Prices: A scatter plot showing how well the predictions match the actual prices.
Cost Function Convergence: A line plot showing how the cost decreases over iteratio

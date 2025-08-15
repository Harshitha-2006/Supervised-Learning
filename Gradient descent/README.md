Gradient Descent Implementation
It predicts a linear relationship between input(x) and output(y) without using machine learning libraries.

Example dataset:
- x: input values 
- y: output values 
The code updates the slope(m) and intercept(b) iteratively to minimize the mean squared error.

How it works:
1. Initialize slope(m) and intercept(b) to 0.
2. Predict y values: y_pred=m*x+b
3. Compute cost(mean squared error)
4. Compute gradients for slope and intercept
5. Update m and b using the gradients
6. Repeat for a set number of iterations

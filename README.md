# Linear Regression — From Scratch (with NumPy)

This project is my hands-on implementation of **Linear Regression** from the ground up, using only NumPy — no sklearn shortcuts, no libraries doing the math for me.  
I wanted to understand how the algorithm really learns those "m" (slope) and "c" (intercept) values through gradient descent, step by step.

# What’s Inside

The core of the project is a custom Linear_regression class that:
- Performs forward propagation (y = m*x + c)
- Computes gradients manually for backward propagation
- Updates parameters using gradient descent
- Tracks the loss (MSE) across iterations
- Visualizes both the fitted regression line and loss convergence

Everything is written cleanly and kept minimal, so it’s easy to follow the math.

# How It Works

We start with random values for "m" and "c", and update them iteratively to minimize the mean squared error (MSE):
Each iteration adjusts "m" and "c" slightly in the direction that reduces the error.

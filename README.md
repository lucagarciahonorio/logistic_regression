# Logistic Regression Comparison

This project implements **Logistic Regression** using two approaches:
1. **Manual implementation** using NumPy.
2. **Using Scikit-learn's `LogisticRegression` model**.

## Features
- Implements the logistic function manually.
- Computes the model parameters using gradient descent.
- Uses Scikit-learn's built-in logistic regression model.
- Calculates various classification metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- Compares and visualizes the results.

## Installation
To run this project, install the required dependencies:

```bash
pip install numpy matplotlib scikit-learn scipy
```

## Usage
Run the Python script to compute and compare logistic regression results:

```bash
python logistic_regression_comparison.py
```

## Expected Output
The script will print evaluation metrics for both implementations and generate a comparison plot.

## Visualization
- **Blue scatter points:** Actual data points.
- **Red line:** Predicted probability from the manual implementation.
- **Green dashed line:** Predicted probability from Scikit-learn.


---
**Author:** Luca Garcia


Nairobi Office Price Prediction
Project Overview
This project implements a linear regression model from scratch to predict office prices in Nairobi based on office size. The implementation includes custom functions for Mean Squared Error calculation and Gradient Descent optimization.
Dataset Description
The dataset (Nairobi Office Price Ex (1).csv) contains information about office spaces in Nairobi, including:

Office size (in square feet)
Office price
Additional features (not used in this implementation) such as:

Location (LOC)
Furnished status (FUR)
Ambiance (AMB)
Proximity to schools, roads, and malls
Water availability
Housekeeping services



Implementation Details
Key Components

Mean Squared Error (MSE) Function

Implements the formula: MSE = (1/n) * Σ(y_true - y_pred)²
Used as the performance measure technique


Gradient Descent Function

Updates weights using partial derivatives
Learning rate: 0.0001
Parameters updated:

Slope (m)
Y-intercept (c)




Model Training

Epochs: 10
Random initialization of weights
Progress tracking with MSE per epoch



Technical Requirements
pythonCopy# Required Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
How to Run

Clone the repository:

bashCopygit clone [your-repository-url]

Install required packages:

bashCopypip install pandas numpy matplotlib

Run the script:

bashCopypython linear_regression.py
Project Structure
Copy├── README.md
├── linear_regression.py
└── Nairobi Office Price Ex (1).csv
Features

Custom implementation of Linear Regression
Visualization of the regression line
Price prediction for new office sizes
Training progress monitoring
Data visualization

Results
The model:

Trains for 10 epochs
Displays MSE for each epoch
Shows the final regression line plot
Provides price prediction for 100 sq. ft. office space

Future Improvements

Implement k-fold cross-validation
Add feature scaling
Include multiple feature support
Add regularization
Implement early stopping

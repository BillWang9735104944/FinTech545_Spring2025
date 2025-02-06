# Project 01 - Statistical Analysis and Covariance Computation

## Overview
This project performs statistical analysis on datasets and computes the covariance matrix. The notebook includes:
- Mean, variance, skewness, and kurtosis calculations.
- Fitting data to normal and t-distributions.
- Conducting Kolmogorov-Smirnov (K-S) tests.
- Computing the pairwise covariance matrix.
- Checking if a covariance matrix is positive semi-definite.

## Requirements
Ensure you have the following Python libraries installed before running the notebook:
```bash
pip install pandas scipy numpy
```

## Files Required
- `problem1.csv` - Dataset for statistical analysis.
- `problem2.csv` - Dataset for covariance matrix computation.

Ensure these files are in the same directory as the notebook.

## Running the Notebook
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Project01.ipynb
   ```
2. Run all cells sequentially.

## Output
- Prints summary statistics (mean, variance, skewness, kurtosis).
- Displays fitted parameters for normal and t-distributions.
- Shows results of K-S tests.
- Computes and prints the covariance matrix.
- Determines if the covariance matrix is positive semi-definite.

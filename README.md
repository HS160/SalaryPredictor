# SalaryPredictor

A simple machine learning project that predicts salary based on years of experience using linear regression.

## Overview

This project implements a simple linear regression model to predict salaries based on years of professional experience. It demonstrates the fundamental steps of a machine learning workflow, including data loading, preprocessing, model training, prediction, and visualization.

## Features

- Loads salary data from a CSV file
- Splits data into training and test sets
- Trains a linear regression model on the training data
- Predicts salaries for the test set
- Visualizes both training and test results with matplotlib

## Dependencies

- Python 3.x
- NumPy
- pandas
- scikit-learn
- matplotlib

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/HS160/SalaryPredictor.git
   cd SalaryPredictor
   ```

2. Install the required dependencies:
   ```
   pip install numpy pandas scikit-learn matplotlib
   ```

3. Make sure you have the data file `Salary_Data.csv` in the project directory.

## Usage

Run the main script:
```
python salary_predictor.py
```

The script will:
1. Load the salary data
2. Split the data into training and test sets
3. Train a linear regression model
4. Display two visualization plots:
   - Training data with regression line
   - Test data with regression line

## Data Format

The expected format for `Salary_Data.csv` is:
- Column 1: Years of Experience
- Column 2: Salary

## Results

The model creates a linear relationship between years of experience and salary, allowing for predictions of expected salary based on experience level.

## Author

HS160

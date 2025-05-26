# Sonar Rock vs Mine Classification

This is a simple machine learning project that uses **Logistic Regression** to classify objects as either **Rock** or **Mine** based on sonar signal data. The dataset used is from the UCI Machine Learning Repository.

## Dataset

- The dataset contains 208 instances with 60 numerical features.
- Each feature represents the energy of a sonar signal at a specific frequency.
- The label (`R` or `M`) indicates whether the object is a **Rock (R)** or a **Mine (M)**.

## Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn

## How It Works

1. Load the dataset using pandas.
2. Split the data into training and test sets.
3. Train a Logistic Regression model on the training data.
4. Evaluate the model's performance using accuracy score.
5. Make predictions on new input data.

## Steps to Run

1. Make sure Python is installed.
2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn
        Download the dataset and save it as sonar data.csv in your working directory.

Example Prediction
Example input:
input_data = (0.0307, 0.0523, 0.0653, 0.0521, 0.0611, ..., 0.0055)
Predicted Output:
['R']
The object is a Rock
Model Performance
Training Accuracy: ~83%
Test Accuracy: ~76%
Note: Accuracy may vary slightly due to the random nature of train-test split.
Reference
Dataset: UCI Sonar Dataset
Author: Prafullit Bhattacharya
Date: May 2025

# Fraud Detection Project

## Overview:

This project uses a Random Forest Classifier to detect fraudulent transactions in financial data.

## Key Steps:

1. **Data Loading and Exploration:**
   - Reads 'fraud.csv' into a Pandas DataFrame.
   - Checks for missing values and provides basic statistics.

2. **Feature Engineering and Preprocessing:**
   - Encodes 'type' using Label Encoding.
   - Removes duplicates and unnecessary columns.

3. **Data Splitting:**
   - Splits data into features (X) and target variable (y).

4. **Model Training and Evaluation:**
   - Trains a Random Forest Classifier.
   - Evaluates model performance.

5. **Visualizations:**
   - Plots feature importance.
   - Creates a scatter plot for data visualization.

6. **Class Imbalance Handling:**
   - Balances classes using resampling techniques.

7. **Visualizations for Resampled Data:**
   - Plots feature importance for resampled data.
     ------------------------------------------------------------------------------------------------


     ## Credits:

- **Random Forest Classifier implementation:** [Scikit-learn](https://scikit-learn.org/)

## Future Work:

- **Implement real-time prediction functionality.**
  - Explore methods to make predictions in real-time for immediate fraud detection.

- **Explore deep learning models for improved accuracy.**
  - Investigate the application of deep learning techniques to enhance the model's accuracy in fraud detection scenarios.


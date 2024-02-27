# Building Insurance Claim Prediction

This repository contains a predictive model for building insurance claims. The model predicts if a building will have an insurance claim during a certain period based on building characteristics.

## Project Overview

1. **Data Preprocessing**: The provided datasets (training and test) were cleaned to handle missing values and irrelevant data. Numerical features were filled with either mode or median based on their distribution.

2. **Feature Selection**: Features were selected based on correlation and feature importance. The selected features are `Building Dimension`, `Date_of_Occupancy`, `YearOfObservation`, `Insured_Period`, `Building_Type`, and `Residential`.

3. **Model Training and Evaluation**: The main data was split into a training set (80%) and a test set (20%). Different models were evaluated, and the Logistic Regression model with parameters `{'C': 1, 'penalty': 'l2'}` was selected with an accuracy of 78%.

4. **Test Data Preprocessing and Prediction**: The test data was preprocessed in the same way as the main data. Predictions were generated and saved as a CSV file.

## Future Work

The next step is to deploy the model for practical use.

Please refer to the detailed report for more information. Contributions and suggestions are welcome!


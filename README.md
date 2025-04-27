# Customer Flight Booking Prediction Using Random Forest

## Overview

This project aims to predict whether a customer will complete a flight booking using a Random Forest classifier. The dataset includes various features such as number of passengers, sales channel, flight day, and more. By applying machine learning and data analysis techniques, this model achieves an accuracy of 85.41%.

## Project Objective

The primary goal of this project was to build a machine learning model that predicts customer flight bookings based on the features provided. The project includes the following key steps:

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Building: Random Forest Classifier
4. Model Evaluation

## Steps Involved

### 1. Data Cleaning and Preprocessing
   - Loaded the dataset and checked for missing values.
   - Encoded categorical variables using Label Encoding.
   - Performed feature transformations (e.g., converting `flight_day` from string to numerical values).

### 2. Exploratory Data Analysis (EDA)
   - Conducted EDA to understand the distribution and relationships between features.
   - Visualized data distributions to uncover insights for feature engineering.

### 3. Model Building: Random Forest Classifier
   - Split the data into training and testing sets.
   - Built a Random Forest model with 100 estimators.
   - Evaluated the model performance using classification metrics.

### 4. **Model Evaluation**
   - Achieved an accuracy of 85.41% on the test data.
   - Generated a detailed classification report highlighting precision, recall, and F1-scores.

## Technologies Used

- Python 3.
- Libraries: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn

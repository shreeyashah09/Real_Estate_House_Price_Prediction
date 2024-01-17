# Real Estate House Price Prediction

## Overview
This project aims to predict house prices based on various features such as square footage, number of bedrooms, location, etc. It utilizes a linear regression model to analyze historical data and forecast prices for real estate.

## Dataset
The dataset used in this project is 'Real_estate.csv,' containing information about different real estate properties. The features include 'No,' 'X1 transaction date,' 'X2 house age,' 'X3 distance to the nearest MRT station,' 'X4 number of convenience stores,' 'X5 latitude,' and 'X6 longitude.'

## Steps Taken

### 1. Data Loading and Exploration
- Imported necessary libraries: pandas, numpy, seaborn, and matplotlib.
- Loaded the dataset into a pandas DataFrame.
- Displayed the first few rows of the dataset 

### 2. Data Cleaning
- The dataset appears to be relatively clean, with no missing values.

### 3. Feature Selection
- Selected features for model training: 'No,' 'X1 transaction date,' 'X2 house age,' 'X3 distance to the nearest MRT station,' 'X4 number of convenience stores,' 'X5 latitude,' and 'X6 longitude.'

### 4. Data Splitting
- Split the data into features (X) and the target variable (y).
- Used `train_test_split` to split the dataset into training and testing sets.

### 5. Model Training
- A linear regression model has been trained using the selected features to predict house prices. The model's coefficients `reg.coef_` and intercept `reg.intercept_` have been calculated, indicating the contribution of each feature to the predicted house
price.

### 6. Model Evaluation
- The performance of the linear regression model has been evaluated on the test set using the reg.score() method.
- The model's accuracy on the test set is provided as a score.

### 7. Visualization
- Created scatter plots using seaborn to visualize the relationships between certain features and the target variable.
  - Age of the house vs. House price of unit area.
  - Distance to the nearest MRT station vs. House price of unit area.
  - Number of convenience stores vs. House price of unit area.

### 8. Insights (Based on Plots):
- Scatter plots show the relationships between house age and house price, distance to the nearest MRT station and house price, and number of convenience stores and house price.
- These plots provide a visual understanding of how these features may influence house prices.



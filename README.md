# Solar-Power-Prediction-using-Polynomial-Regression
Machine Learning project that predicts solar power generation using Polynomial Regression based on temperature, humidity, wind speed, and solar incidence angle data🌞

## Overview

This project predicts solar power generation using environmental and weather-related parameters. A Polynomial Regression model is trained on historical solar power generation data to estimate the amount of power generated under different atmospheric conditions.

The project demonstrates the application of Machine Learning in the renewable energy sector to improve energy forecasting and decision-making.

## Features
Data preprocessing and cleaning
Exploratory data inspection
Polynomial feature generation
Polynomial Regression model training
Model evaluation using:
  -Mean Squared Error (MSE)
  -R² Score
Visualization of Actual vs Predicted Power Generation

##Dataset Attributes
The model uses the following input features:

## Feature	Description
temperature_2_m_above_gnd	--> Temperature above ground level
relative_humidity_2_m_above_gnd	--> Relative humidity
angle_of_incidence --> Angle of solar incidence
wind_speed_10_m_above_gnd	--> Wind speed above ground level

## Target Variable
generated_power_kw

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook

## Machine Learning Workflow
1. Load and inspect dataset
2. Check for missing values
3. Select input features and target variable
4. Split dataset into training and testing sets
5. Generate polynomial features
6. Train Polynomial Regression model
7. Predict solar power generation
8. Evaluate model performance
9. Visualize prediction results

## Model Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score

These metrics help assess the accuracy and reliability of the prediction model.

## Output Visualization

The notebook generates a scatter plot comparing:

- Actual Solar Power Generation
- Predicted Solar Power Generation

This helps visualize model performance and prediction accuracy.

# Author
## Ishita Patel

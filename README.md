# Solar Power Prediction using Polynomial Regression

A Machine Learning project that predicts solar power generation using Polynomial Regression based on temperature, humidity, wind speed, and solar incidence angle data.

## Overview

This project predicts solar power generation using environmental and weather-related parameters. A Polynomial Regression model is trained on historical solar power generation data to estimate the amount of power that can be generated. The project demonstrates the application of Machine Learning in the renewable energy sector to improve energy forecasting and decision-making.

## Features

- Data preprocessing and cleaning
- Exploratory data inspection
- Polynomial feature generation
- Polynomial Regression model training
- Model evaluation metrics:
  - Mean Squared Error (MSE)
  - R² Score
- Visualization of Actual vs Predicted Power Generation

## Dataset Attributes

The model uses the following input features:

| Feature | Description |
|---------|-------------|
| `temperature_2_m_above_gnd` | Temperature above ground level (°C) |
| `relative_humidity_2_m_above_gnd` | Relative humidity (%) |
| `angle_of_incidence` | Angle of solar incidence (degrees) |
| `wind_speed_10_m_above_gnd` | Wind speed above ground level (m/s) |

### Target Variable

- `generated_power_kw` - Solar power generated (kW)

## Technologies Used

- Python 3.x
- Pandas - Data manipulation and analysis
- NumPy - Numerical computing
- Matplotlib - Data visualization
- Scikit-learn - Machine learning library
- Jupyter Notebook - Interactive development environment

## Machine Learning Workflow

1. Load and inspect dataset
2. Check for missing values
3. Select input features and target variable
4. Split dataset into training and testing sets (e.g., 80-20 split)
5. Generate polynomial features
6. Train Polynomial Regression model
7. Predict solar power generation
8. Evaluate model performance
9. Visualize prediction results

## Model Evaluation Metrics

### Mean Squared Error (MSE)
Measures the average squared difference between predicted and actual values. Lower MSE indicates better model performance.

### R² Score
Represents the proportion of variance explained by the model. Values range from 0 to 1, with 1 indicating perfect predictions.

These metrics help assess the accuracy and reliability of the prediction model.

## Output Visualization

The notebook generates a scatter plot comparing:

- **Actual Solar Power Generation** - Real values from the test set
- **Predicted Solar Power Generation** - Values predicted by the model

This visualization helps identify model performance and prediction accuracy.

## Getting Started

### Prerequisites
- Python 3.x installed
- Required libraries (see Technologies Used section)

### Installation

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### Usage

1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells to train the model and generate predictions
4. Review the visualizations and evaluation metrics

## Author

👤 **Ishita Patel**

---


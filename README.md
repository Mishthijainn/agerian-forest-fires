# Algerian Forest Fire Prediction

This project aims to predict forest fire occurrences in Algeria using a dataset of historical fire data. The analysis and prediction were performed using the **Lasso regression** algorithm to determine the impact of various meteorological and environmental factors on the likelihood of forest fires.

## Project Overview

The goal of this project is to analyze and predict forest fire events in Algeria, utilizing data-driven insights. By identifying the key factors that contribute to forest fires, we can make more informed decisions to mitigate fire risks in the future.

## Dataset

The dataset used in this project is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Forest+Fires) and contains historical records of forest fires in Algeria. The data includes various features such as:
- Temperature
- Humidity
- Wind speed
- Rainfall
- Month of the year
- Day of the week
- and more...

## Tools & Libraries Used

- **Python**: Programming language used for analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning (Lasso regression model).
- **Jupyter Notebooks**: Interactive development environment.

## Data Analysis & Feature Engineering

1. **Exploratory Data Analysis (EDA)**:
   - Data cleaning and preprocessing.
   - Visualization of the data to understand patterns.
   - Identifying correlations between features and fire occurrences.

2. **Feature Engineering**:
   - Conversion of categorical variables to numeric values (e.g., months, days).
   - Handling missing values and scaling numerical features.

## Predictive Modeling

- **Lasso Regression**: A linear model with L1 regularization to predict the occurrence of forest fires. Lasso regression helps to identify the most important features while preventing overfitting.
- Model evaluation using metrics like **Mean Squared Error (MSE)** and **R-squared**.

## Steps to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Mishthijainn/agerian-forest-fires.git

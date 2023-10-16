# Data-Science---Multiple-Linear-Regression-MLR-
# Toyota Corolla Price Prediction Model

## Problem Statement

The goal of this project is to build a predictive model for predicting the price of Toyota Corolla cars based on specific features. The features include 'Age_08_04', 'KM', 'HP', 'cc', 'Doors', 'Gears', 'Quarterly_Tax', and 'Weight'. The problem is approached using linear regression techniques.

## Data

The dataset used in this project is sourced from the 'ToyotaCorolla.csv' file. It contains information about various Toyota Corolla cars, with specific features and the target variable 'Price'.

### Data Exploration and Preprocessing

- Shape of the dataset.
- Descriptive statistics of the dataset.
- Correlation analysis.
- Visualization through pairplots and heatmaps.
- Initial model preparation using 'statsmodels' library.

## Model Building

Key steps in model building:

1. Data preparation: Selection of relevant features.
2. Building the initial model.
3. Evaluation of the model, including checking for collinearity and homoscedasticity.
4. Detection of influential data points and outliers.
5. Improving the model by removing outliers.
6. Building the final model.

## Model Evaluation

- R-squared values for the basic and final models.
- Predicting car prices based on the model.

## Residual Analysis

- Q-Q Plot for checking normality of residuals.
- Residual Plot for homoscedasticity.
- Residual vs. Regressors plots for examining the relationships between residuals and predictor variables.

## Influential Data Points

- Cook's Distance to identify influential data points.
- Removing influential data points for model improvement.

## Prerequisites

Before running the code, make sure you have the following libraries installed:

- pandas
- numpy
- seaborn
- matplotlib
- statsmodels
- statsmodels.api
- statsmodels.formula.api

You can install them using `pip install`.

## Usage

1. Download the 'ToyotaCorolla.csv' dataset.
2. Run the code provided in the respective sections of the project structure.
3. Explore the README file to understand the process, visualizations, and results.
4. Use the code as a starting point for price prediction modeling projects.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please open an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Explore the world of predictive modeling for car prices with Toyota Corolla data!

50 STARTUP DATASET:
# 50 Startups Profit Prediction Model

## Problem Statement

The objective of this project is to develop a prediction model for the profit of 50 startups. The dataset, containing various features such as 'R&D Spend,' 'Administration,' 'Marketing Spend,' and 'Profit,' is used for model creation and analysis. The goal is to transform the data for improved profit predictions.

## Data and Libraries

The dataset used in this project is '50_Startups.csv'. The following libraries are used for analysis and modeling:

- pandas
- seaborn
- matplotlib.pyplot
- statsmodels

## Data Exploration and Preprocessing

- Reading the dataset and initial exploration.
- Feature engineering and renaming for better understanding.
- Correlation analysis and visualization using pairplots and heatmaps.

## Model Building

1. Building the initial model with 'Profit' as the target variable and 'R&D Spend,' 'Administration,' and 'Marketing Spend' as predictors.
2. Model summary, validation, and checking for multicollinearity (VIF).

## Residual Analysis

- Q-Q Plot for checking normality of residuals.
- Residual Plot for homoscedasticity.
- Residual vs. Regression plots to examine the relationships between residuals and predictor variables.

## Model Validation and Improvement

- Detecting influential data points and outliers using Cook's Distance.
- Removing outliers to improve the model.
- Building the final model.

## Model Evaluation

- Comparing R-squared values of the basic and final models.
- Predicting profit based on the final model.

## Prerequisites

Ensure you have the required libraries installed using `pip install`.

## Usage

1. Download the '50_Startups.csv' dataset.
2. Run the provided code in the corresponding sections to perform data exploration, preprocessing, model building, analysis, and predictions.
3. Examine the README file to understand the project's process and results.
4. Use this code as a foundation for profit prediction modeling projects.

## Contributing

Contributions and improvements to the code are welcome. Feel free to open an issue or a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Explore the world of profit prediction for startups using data transformation and regression modeling!


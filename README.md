# Global-CO2-Emissions-Analyzing-Economic-and-Policy-Impact

---

## Project Overview

This project investigates the key factors influencing per capita CO2 emissions across nations, examining both macroeconomic and policy-related aspects. The study aims to identify significant contributors to CO2 emissions and provide insights into potential areas for environmental policy development.

## Motivation

Reducing carbon emissions and mitigating global warming effects are critical 21st-century policy challenges due to their projected impact on the global economy. This project explores how factors like GDP per capita, industry share, urbanization, technology growth, fossil fuel subsidies, and renewable energy adoption correlate with CO2 emissions.

## Data Description

- **Dependent Variable**: Per Capita CO2 Emissions.
- **Independent Variables**:
  - Fossil Fuel Subsidies per Capita
  - Population
  - Per Capita GDP (PPP, 2017 Constant USD)
  - Per Capita Energy Consumption
  - Renewable Energy Share
  - Industry Share
  - GII Technology Index
  - Urbanization

Sources include the Global Carbon Budget, World Bank, International Energy Agency, and UN databases.

## Installation and Setup

1. Install the necessary libraries:
    ```bash
    pip install numpy pandas matplotlib seaborn statsmodels scikit-learn
    ```
2. Import the dataset and preprocess using the provided cleaning steps.

## Usage

### Descriptive Analysis

1. **Histograms and Density Plots**: Examine the distributions of key variables.
2. **Correlation Analysis**: Identify relationships between CO2 emissions and potential predictors.

### Regression Analysis

- **Model Fitting**: Linear regression models were applied to understand the influence of each predictor on CO2 emissions.
- **Box-Cox Transformations**: Applied to handle non-linearities.

### Outlier Detection

- **Leverage and Residual Plots**: Diagnose high-leverage points and influential observations.

## Features

- Exploratory Data Analysis (EDA)
- Regression Modeling with Box-Cox transformations for non-linearity handling
- Outlier and leverage diagnostics for identifying influential observations
- Imputation of missing values using KNN

## Contributing

To contribute, please ensure code adheres to the project’s coding standards and submit a pull request. All contributions are welcome!

## License

This project is licensed under the MIT License.

---


Energy Consumption Forecasting with Regression Models

**Project Overview**

This project uses historical global energy consumption data (1965–2023) to build regression-based time series forecasting models in Python. The objective is to predict future energy demand using engineered temporal features and to evaluate model performance under different scenarios.

This project is part of a personal data science portfolio and demonstrates time series modeling, feature engineering, and regression performance evaluation.

**Dataset Description**

The dataset World_Energy_By_Country_And_Region_1965_to_2023.csv contains yearly energy consumption values (in exajoules) for countries and regions from 1965 to 2023.

Rows: Countries or regions (e.g., Canada, US, Europe, Asia Pacific)

Columns: Years from 1965 to 2023

Values: Annual energy consumption (Exajoules)

**Problem Statement**

Forecast future energy consumption using historical trends by building and comparing different regression models. Analyze how engineered features improve prediction accuracy.

**Methodology**

**Data Preparation:**

Transformed wide-format time series into long-format (year-wise rows)

Handled missing values and aligned data types

**Feature Engineering:**

Previous year’s consumption (lag_1)

3-year rolling average (rolling_3)

Region as categorical feature

**Modeling Approach:**

Built multiple regression models:

Base model with year as predictor

Model with lag and rolling features

Trained on historical data, validated on recent years

**Evaluation Metrics:**

Mean Squared Error (MSE)

R-squared (R²)

Compared performance across scenarios

**Visualization:**

Forecast vs actual line plots

Residual analysis to assess model bias

**Key Questions Answered**

How well can a regression model forecast energy consumption using historical trends?

Do lag features or rolling averages improve model accuracy?

What regions or countries show predictable vs volatile energy patterns?

**Results & Insights**

Models using lag and rolling features consistently outperformed simple linear models

Countries with stable consumption trends (e.g., Canada, US) had higher R² scores

Rolling average features helped smooth volatility in emerging economies

**Skills Demonstrated**

Time series transformation & visualization

Feature engineering for temporal data

Regression modeling in Python (scikit-learn, pandas)

Model evaluation using MSE and R²

Forecasting and comparative analysis

**Project Files**

Time Series Forecasting.ipynb – Full notebook with EDA, modeling, evaluation

World_Energy_By_Country_And_Region_1965_to_2023.csv – Raw energy consumption data

**How to Use**

Clone the repo and open the Jupyter notebook

Install dependencies: pandas, numpy, matplotlib, scikit-learn

Run all cells in sequence to reproduce results and plots

This project is part of my data science portfolio to showcase applied regression forecasting techniques on real-world energy datasets.



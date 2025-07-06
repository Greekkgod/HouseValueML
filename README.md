# California Housing Price Prediction

This project focuses on predicting housing prices in California using machine learning techniques. It is built around a structured data science pipeline that includes data cleaning, feature engineering, model training, evaluation, and visualization.

## Project Objective

The goal is to develop a regression model that can accurately predict median house values based on features like location, number of rooms, population, and other housing-related factors. The project is based on the California housing dataset.

## Key Features

- Cleaned and explored the dataset to understand feature relationships
- Engineered new features such as:
  - Rooms per household
  - Population per household
- Built a preprocessing pipeline using Scikit-learn tools like:
  - `SimpleImputer` for handling missing values
  - `StandardScaler` for feature scaling
  - `ColumnTransformer` for column-wise transformations
- Trained and evaluated models using:
  - Linear Regression
  - Decision Tree Regressor
- Used root mean squared error (RMSE) and cross-validation to measure model performance

## Tools and Technologies

- Python
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for data visualization
- Scikit-learn for building the ML pipeline
- Jupyter Notebook for development and experimentation

## Visualizations

- Correlation heatmaps to identify important features
- Histograms to understand data distribution
- Error distribution plots to analyze model performance


# Melbourne Real Estate Price Prediction

This repository contains a machine learning project aimed at predicting real estate prices in Melbourne using historical sales data. The project involves various stages including data exploration, cleaning, feature engineering, and model building with multiple machine learning algorithms.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Cleaning and Feature Engineering](#data-cleaning-and-feature-engineering)
- [Model Building](#model-building)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The objective of this project is to develop a predictive model for real estate prices in Melbourne. By leveraging various machine learning techniques, the goal is to create accurate models that can help in understanding the factors influencing property prices and provide reliable predictions.

## Dataset
The dataset used in this project is from [Melbourne Housing Market](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot). It contains data on house sales in Melbourne, including features such as the number of rooms, type of property, location, and sale price.

## Exploratory Data Analysis (EDA)
The EDA phase includes:
- **Univariate Analysis**: Understanding the distribution of individual variables.
- **Bivariate Analysis**: Investigating relationships between pairs of variables.
- **Visualization**: Using histograms, scatter plots, and heatmaps to identify patterns and correlations.

## Data Cleaning and Feature Engineering
Key steps in this phase:
- **Handling Missing Values**: Imputation strategies for filling missing data.
- **Outlier Removal**: Using the Interquartile Range (IQR) method to identify and remove outliers.
- **Dimensionality Reduction**: Reducing the number of dummy variables by classifying suburbs with fewer than 10 data points as 'others'.

## Model Building
The following models were built and evaluated:
- **Linear Regression with Cross-Validation**:
  - Created a pipeline for preprocessing and model training.
  - Performed 10-fold cross-validation and calculated metrics like Mean Squared Error (MSE) and adjusted R-squared.
  
- **Random Forest with Hyperparameter Tuning**:
  - Used GridSearchCV for hyperparameter tuning.
  - Evaluated the model on the test set.

- **Gradient Boosting with Hyperparameter Tuning**:
  - Trained a Gradient Boosting Regressor using GridSearchCV.
  - Assessed the model’s performance on the test set.

## Results
Key findings and visualizations:
- **Distributions and Relationships**: Histograms and scatter plots to understand the data.
- **Correlation Analysis**: Heatmap of the correlation matrix to identify strong relationships between features.
- **Model Performance**: Evaluation metrics and visualizations comparing actual vs. predicted values for each model.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests to contribute.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




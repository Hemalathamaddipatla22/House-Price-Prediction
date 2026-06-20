# House Price Prediction Using Machine Learning

## Overview

This project predicts house prices using machine learning techniques. The dataset contains information about house characteristics such as area, bedrooms, bathrooms, stories, parking spaces, and amenities. The goal is to analyze the factors affecting house prices and build predictive models.

## Dataset

* Dataset Name: Housing Prices Dataset
* Source: Kaggle
* Number of Records: 545
* Target Variable: Price

## Project Workflow

### 1. Data Preparation

* Loaded the housing dataset.
* Explored dataset structure and features.
* Selected relevant features for price prediction.

### 2. Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Converted categorical variables into numerical format using one-hot encoding.

### 3. Model Building

Two machine learning models were trained:

#### Linear Regression

* MAE: 932,640.44
* RMSE: 1,251,802.93
* R² Score: 0.5503

#### Random Forest Regressor

* MAE:  953420.79
* RMSE: 1,292,181.38
* R² Score: 0.5208

### Model Comparison

The Linear Regression model achieved slightly better performance than the Random Forest Regressor with lower prediction errors and a higher R² score.

## Visualizations

The following visualizations were created:

1. Histogram of House Price Distribution
2. Correlation Heatmap of Housing Features
3. Actual vs Predicted House Prices Scatter Plot

## Key Findings

* Area is the strongest factor influencing house prices.
* Bathrooms, stories, and air conditioning also contribute significantly.
* Larger houses generally have higher prices.
* The model explains approximately 55% of the variation in house prices.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Conclusion

This project successfully developed a house price prediction model using machine learning. After evaluating multiple models, Linear Regression was selected as the best-performing model for this dataset. The analysis highlights the importance of property size and amenities in determining house prices.


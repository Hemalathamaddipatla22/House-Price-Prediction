# House Price Prediction Using Machine Learning

## Project Overview

This project aims to predict house prices using machine learning techniques based on various housing features such as area, number of bedrooms, bathrooms, stories, parking spaces, and amenities. The project includes data cleaning, exploratory analysis, model building, evaluation, and visualization.

## Dataset

* Dataset: Housing Prices Dataset
* Source: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset
* Records: 545 houses
* Target Variable: `price`

## Project Objectives

* Clean and preprocess housing data.
* Handle missing values and duplicates.
* Convert categorical features into numerical format using one-hot encoding.
* Train machine learning models to predict house prices.
* Evaluate model performance using MAE, RMSE, and R² Score.
* Visualize important patterns and relationships in the data.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Data Preprocessing

* Checked and handled missing values.
* Removed duplicate records.
* Applied one-hot encoding to categorical variables.
* Selected meaningful features for prediction.

## Models Used

### 1. Linear Regression

Performance:

* MAE: 932,640.44
* RMSE: 1,251,802.93
* R² Score: 0.5503

### 2. Random Forest Regressor

Performance:

* MAE: 953420.79
* RMSE: 1,292,181.38
* R² Score: 0.5208

## Model Comparison

The Linear Regression model performed slightly better than the Random Forest Regressor on this dataset, achieving lower error values and a higher R² score.

## Visualizations

1. Histogram of House Price Distribution
2. Correlation Heatmap of Housing Features
3. Actual vs Predicted House Prices Scatter Plot

## Key Findings

* Area is the most influential factor affecting house prices.
* Bathrooms, stories, and air conditioning also have a significant impact.
* Houses with similar areas may have different prices due to amenities and location-related factors.
* The Linear Regression model explains approximately 55% of the variation in house prices.

## Recommendation

Real estate businesses should focus on properties with larger areas and better amenities, as these features contribute significantly to higher property values and customer demand.

## Conclusion

This project successfully developed a house price prediction system using machine learning. After comparing two models, Linear Regression provided the best performance and was selected as the final model for predicting house prices.


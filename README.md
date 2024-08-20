# Predictive Modeling of Used Car Prices with Linear Regression

## Overview
This project aims to apply linear regression techniques to predict the prices of used cars in the US and Canada. Utilizing a comprehensive dataset from MarketCheck, the project explores key factors influencing car prices and offers insights into market trends.

## Project Structure
- **Report**: The detailed analysis is available in the `DataSci - Midterm.pdf` file, which includes data preprocessing steps, statistical analysis, and model evaluation.
- **Data**: The dataset includes used car listings with features like year, make, model, mileage, and more, gathered from dealer websites across the US and Canada.
- **Scripts**: Python scripts used for data cleaning, feature engineering, and model training are provided in the `scripts/` directory.

## Key Objectives
- **Price Prediction**: Develop a linear regression model to predict car prices based on various features.
- **Market Insight**: Analyze trends in the used car market to identify factors influencing prices and demand.
- **Data Preprocessing**: Handle missing values, scale features, and encode categorical variables to prepare the data for modeling.
- **Model Evaluation**: Assess model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Data Preprocessing
- **Missing Values**: Imputed missing values for numerical features like mileage and engine size using mean values, and for categorical features using the mode.
- **Feature Engineering**: Applied polynomial feature engineering to enhance model performance.
- **Data Splitting**: Separated the dataset into training and test sets to evaluate the model's predictive accuracy.

## Model Development
- **Linear Regression**: Implemented a baseline linear regression model.
- **Polynomial Regression**: Enhanced the model by adding polynomial features to capture non-linear relationships.
- **Model Validation**: Used cross-validation techniques to assess the model's generalizability and performance consistency.

## Results
- **Model Performance**: The polynomial regression model showed improved accuracy, with lower MAE and MSE, and higher R-squared compared to the baseline linear model.
- **Market Insights**: The analysis revealed significant trends in price depreciation with mileage and brand influence on resale value.

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction

# Decoding Real Estate Dynamics: A Machine Learning Approach to Housing Price Forecasting

## Project Overview
This project examines the integration of Machine Learning (ML) techniques to enhance predictive accuracy in the housing market, particularly focusing on villa prices in Saudi Arabia. The study develops and compares three distinct predictive models: Simple Linear Regression (SLR), Random Forest (RF), and Extreme Gradient Boosting (XGBoost), using a dataset comprising 46,826 records from the Riyadh villas market. The aim is to identify the most effective ML model based on standard evaluation metrics and predictive accuracy.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
  - [Data Collection](#data-collection)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Model Development](#model-development)
  - [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [References](#references)

## Introduction
Housing is a critical aspect of human existence, influencing the stability of countries economically and the dynamics of societies socially. With advancements in technology, particularly in Machine Learning, opportunities to enhance various aspects of the housing sector have increased. This project aims to leverage ML techniques to predict villa prices in Saudi Arabia accurately.

## Methodology

### Data Collection
The dataset used in this study comprises 46,826 records from the Riyadh villas market. Key features include location, space, and amenities like pools and elevators.

### Data Cleaning
Comprehensive data cleaning was performed to ensure the accuracy and reliability of the dataset. Missing values were handled, and irrelevant features were removed.

### Exploratory Data Analysis (EDA)
EDA was conducted to identify key features influencing villa prices. Visualizations and statistical analyses helped uncover patterns and correlations in the data.

### Model Development
Three ML models were developed and compared:
- **Simple Linear Regression (SLR)**: Assumes a linear relationship between dependent and independent variables.
- **Random Forest (RF)**: An ensemble learning method combining multiple decision trees to improve prediction accuracy.
- **Extreme Gradient Boosting (XGBoost)**: A gradient-boosting algorithm that builds models sequentially to correct previous errors.

### Model Evaluation
Models were evaluated based on Mean Absolute Percentage Error (MAPE) and R-squared values. RF demonstrated superior performance with a MAPE of 5% and an R-squared of 96%.

## Results
The RF model slightly outperformed XGBoost, making it the most suitable model for predicting villa prices in this market context. The study aids researchers and investors in understanding the dynamics of real estate pricing and enhances decision-making processes through advanced predictive analytics.

## Conclusion
The project successfully identified the RF model as the most effective for predicting villa prices in Riyadh, Saudi Arabia. This finding provides valuable insights for future research and practical applications in the real estate market.

## Future Work
Future research could explore incorporating additional features and testing other advanced ML algorithms to further improve predictive accuracy. Additionally, expanding the dataset to include other regions and types of properties could enhance the model's generalizability.

## References
- Alsuhaibani, A., Alswailm, M., Alnahdi, K., & Alghamdi, A. (2024). Decoding Real Estate Dynamics: A Machine Learning Approach to Housing Price Forecasting. *Information*, 1(0). https://doi.org/10.3390/info1010000

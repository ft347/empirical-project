# Airbnb Price Prediction - London

## Overview
This project analyses Airbnb listings in London to identify key drivers of price and build predictive models. Using a combination of geographical data and property characteristics, the project aims to provide insights for both hosts (for pricing strategy) and guests (for seeking value).

## Dataset
- Source: Inside Airbnb
- Observations: 46,390 rows
- Features: 21 variables

## Methodology
1. Data Collection: Sourcing raw CSV data from Inside Airbnb
2. Data Cleaning: Handling missing values, removing outliers, and log transforming price to handle skewness
3. Data Analysis: Visualising price distribution and comparing correlations
4. Modelling: Training and evaluating Linear Regression & Random Forest models
5. Conclusion: Evaluating feature importance and the performance of the model

## Key Findings
- The most significant predictor of listing price is whether the property is a "Private Room" or an "Entire Home"
- The number of bathrooms and bedrooms significantly drives listing price
- Longitude and latitude play a crucial role, indicating higher price density in Central London

## Results
Linear Regression R Squared: 0.621
Random Forest Regression R Squared: 0.797

The Random Forest model explains approximately 80% of the variance in London listing prices.

## Visualisations
The feature importance and error analysis plots can be found in the figures/ directory

## How to run
1. **Clone the Repository**:
git clone https://github.com/ft347/empirical-project.git

2. **Install Dependencies**:
pip install -r requirements.txt

3. **Run the Notebooks**:
jupyter notebook
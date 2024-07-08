# BoomBikes Linear Regression Project

## Overview

BoomBikes, a US bike-sharing provider, experienced a significant drop in revenues during the COVID-19 pandemic. To devise a recovery plan, BoomBikes aims to understand the factors influencing bike demand and predict future demand patterns post-lockdown. This project builds a linear regression model to predict daily bike rentals using various meteorological and categorical variables.

## Business Goal

Model the demand for shared bikes to help BoomBikes understand the key factors affecting bike rentals and optimize their business strategy accordingly.

## Dataset

The dataset includes daily records of bike rentals from 2018 to 2019. Key features are:

- **Date and Time**: instant, dteday, yr, mnth, weekday
- **Weather Conditions**: season, temp, atemp, hum, windspeed, weathersit
- **Rental Counts**: casual, registered, cnt (total count)

## Methodology

### Steps Followed:

1. **Data Understanding & Visualization**: Examined data structure and initial correlations.
2. **Data Preparation**: Handled missing values, converted categorical variables, and dropped redundant features.
3. **Feature Selection**: Used correlation and Recursive Feature Elimination (RFE) to choose significant variables.
4. **Model Building**: Developed multiple linear regression models, checked for multicollinearity using Variance Inflation Factor (VIF), and optimized the final model.
5. **Residual Analysis**: Verified model assumptions by analyzing residuals.
6. **Predictions**: Predicted bike rentals and evaluated model performance.
7. **Model Evaluation**: Compared training and testing sets’ R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

### Key Insights:

- **Temperature**: Higher temperatures significantly increase bike rentals.
- **Wind Speed**: Higher wind speeds reduce bike rentals.
- **Seasonality**: Peak rentals occur during the fall and winter seasons, particularly from June to October.
- **Yearly Growth**: Significant increase in rentals from 2018 to 2019.

## Model Performance

- **R-squared**: 
  - Training Set: 83.2%
  - Testing Set: 82.8%
- **Mean Absolute Error (MAE)**: ~0.07 (both sets)
- **Mean Squared Error (MSE)**: ~0.01 (both sets)

The model shows consistent performance, indicating robust and reliable predictions.

## Recommendations

1. **Targeted Marketing**:
   - Focus on promotions during summer and winter.
   - Increase marketing efforts from June onwards to capitalize on higher demand.

2. **Weather-Based Incentives**:
   - Offer discounts or incentives on days with adverse weather to encourage rentals.

3. **Dynamic Pricing**:
   - Adjust pricing on clear days to maximize profits, as these are peak rental days.

4. **Customer Retention**:
   - Analyze customer data to understand and enhance repeat usage patterns.

## Conclusion

This linear regression model provides BoomBikes with a deeper understanding of the factors driving bike rental demand, enabling them to fine-tune their business strategies for better market alignment and profitability.

## Contact

For any questions or further discussions, please contact me at:

- deveshdp31oct@gmail.com

---

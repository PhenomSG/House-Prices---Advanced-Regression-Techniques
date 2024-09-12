# House Prices - Advanced Regression Techniques

This project focuses on predicting house sale prices using a comprehensive dataset of residential homes in Ames, Iowa. The dataset contains 79 explanatory variables that describe various aspects of the homes, such as size, location, quality, and condition.

![Main Image](house.png)

## Project Overview

The goal of this project is to predict the sales price for each house based on its features. The predictions will be evaluated using Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted and actual sale prices. This approach ensures that errors in predicting both expensive and affordable houses are treated equally.

## Dataset

The dataset includes various features about each house, including:
- **Lot size and area**
- **Number of bedrooms and bathrooms**
- **Year built and remodeled**
- **Garage type and size**
- **Quality of materials**
- **Neighborhood and location features**

These features allow us to build a model that can capture the various factors influencing house prices.

## Evaluation Metric

The model's performance is measured by RMSE between the logarithmic values of the predicted and actual sale prices. This ensures a balanced evaluation for houses of different price ranges.

## Acknowledgments

The Ames Housing dataset was compiled by Dean De Cock and is widely used in data science education as an alternative to the Boston Housing dataset.


# Housing-Market-Analysis

Regression analysis of California housing data (1990) to model relationships between predictors and median house values. Provides insights into housing trends for informed investment decisions.

## Project Overview

This repository contains a detailed regression analysis of the California housing market using data from 1990. The goal is to model the relationship between various predictors and median house values, providing valuable insights into the fluctuating housing market. This analysis can assist future workforce entrants and prospective homebuyers in making informed decisions regarding housing investments.

## Dataset

- **Source**: [California Housing Data (1990)](https://www.kaggle.com/datasets/harrywang/housing?select=housing.csv)
- **Variables**: The dataset includes features such as location (longitude, latitude), housing median age, number of rooms, population, median income, and proximity to the ocean.

## Methodology

- **Exploratory Data Analysis (EDA)**:
  - Analyzed quantitative variables using histograms and scatterplots.
  - Examined correlation matrices to identify highly correlated variables.
  - Explored the relationship between ocean proximity and housing prices.
  
- **Regression Modeling**:
  - Performed linear regression using Statsmodel OLS.
  - Validated the model using VIF analysis to address multicollinearity.
  - Conducted K-Fold cross-validation to evaluate model consistency.

## Key Findings

- Median income, housing median age, and ocean proximity are significant predictors of median house values.
- The model explains approximately 64% of the variance in house values.
- Homes closer to the ocean are generally more expensive.

## Conclusion

This analysis reveals that certain factors, such as proximity to the ocean and median income, significantly influence house prices in California. While the model demonstrates good predictive power, further refinements could enhance accuracy, especially by addressing potential outliers.

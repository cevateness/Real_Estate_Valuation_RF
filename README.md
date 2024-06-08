# Real_Estate_Valuation_RF
Real Estate Value Prediction using Random Forest Algorithm


# Real Estate Value Prediction using Random Forest

This study introduces a methodology employing the Random Forest algorithm to predict real estate values. Using a dataset from Sindian Dist., New Taipei City, Taiwan, the research focuses on estimating real estate values through regression. The approach includes data preprocessing, feature selection, parameter tuning, and applying the Random Forest Regression model. Model performance is evaluated using the mean squared error metric, contributing to accurate and reliable real estate value prediction.


## Problem Description
The dataset consists of 414 instances from Sindian Dist., New Taipei City, Taiwan, with features like transaction date, house age, distance to the nearest MRT station, number of convenience stores, and geographical coordinates. The target variable is the house price per unit area (New Taiwan Dollars/Ping). 

## Methodology
### Data Preprocessing and Analysis
- Cleaned and prepared the dataset.
- Examined descriptive statistics and correlation matrices.
- Identified significant features influencing house prices.

### Feature Selection and Hyperparameter Tuning
- Conducted hyperparameter tuning using `RandomizedSearchCV` to optimize the Random Forest model.
- Evaluated feature importance and adjusted model parameters accordingly.

### Random Forest Regression Model
- Implemented the Random Forest Regression algorithm.
- Achieved a mean squared error reduction from 31.14 to 4.99 after tuning.

## Conclusion
This study presents a comprehensive approach to predicting real estate values using the Random Forest algorithm. The methodology emphasizes the importance of hyperparameter tuning to enhance predictive accuracy. While the model performs well on the specific dataset, future research should explore its applicability to different regions and property types.



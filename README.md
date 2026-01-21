# Surprise Housing Price Prediction – Ridge & Lasso Regression
> A machine learning project implementing Ridge and Lasso regression models to predict housing prices with advanced hyperparameter tuning and regularization techniques.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- This project focuses on predicting housing prices using regularized regression models (Ridge and Lasso).
- **Background**: The dataset contains historical housing information with various features that influence property prices.
- **Business Problem**: Accurately predict housing prices to help real estate agencies and buyers make data-driven decisions. By comparing Ridge and Lasso regression, we identify which features are most critical for price prediction.
- **Dataset**: The Surprise Housing dataset contains multiple numerical and categorical features including property characteristics like area, quality, condition, and various amenities. The target variable is the sales price (SalePrice).
- **Data Preprocessing**: The project includes handling missing values (median for numerical, mode for categorical), encoding categorical variables, and feature scaling (mandatory for Ridge and Lasso regression).
- **Model Comparison**: Both Ridge and Lasso regression use GridSearchCV for optimal alpha (regularization strength) tuning across 5 folds.

## Conclusions
- Both Ridge and Lasso regression effectively predict housing prices with comparable performance after hyperparameter tuning.
- Ridge regression is particularly useful for handling multicollinearity in housing datasets where many features are correlated.
- Lasso regression performs feature selection by shrinking less important coefficients to zero, making it easier to identify the most critical predictors.
- The optimal alpha values determined through cross-validation help balance model bias and variance for better generalization.
- Feature scaling is essential for regularized regression models to ensure all features contribute equally to the regularization penalty.
- As alpha increases (stronger regularization), more features are eliminated by Lasso, demonstrating the trade-off between model complexity and interpretability.

## Technologies Used
- Python - 3.x
- pandas - 2.0+
- scikit-learn - 1.0+
- numpy - 1.20+
- matplotlib - 3.5+
- seaborn - 0.12+


## Acknowledgements
Give credit here.
- This project was based on Upgrad's Advanced Regression assignment.
- Ridge and Lasso regression concepts from scikit-learn documentation.
- Housing price prediction is a classic machine learning problem used for educational purposes.


## Contact
Created for Advanced Regression - Assignment 2 (Upgrad)



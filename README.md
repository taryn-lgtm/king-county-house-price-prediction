# King County House Price Prediction

Exploratory data analysis and machine learning applied to residential property sales in King County, Washington.

## Project Overview

Using a dataset of over 21,000 house sales, this project investigates the relationships between property characteristics and selling prices, before developing and evaluating regression models.

Completed as part of the IBM Data Analysis with Python course.

## Technologies

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Jupyter Notebook

## Methods

- Data cleaning and handling missing values
- Exploratory data analysis and statistical summaries
- Correlation analysis and data visualisation
- Simple and multiple linear regression
- Polynomial feature engineering
- Ridge regression and regularisation
- Model evaluation using R²

## Results

| Model | R² | Dataset |
|---|---:|---|
| Simple Linear Regression | 0.4929 | Training |
| Multiple Linear Regression | 0.6577 | Training |
| Polynomial Regression Pipeline | 0.7512 | Training |
| Ridge Regression | 0.6479 | Test |
| Polynomial Ridge Regression | 0.7003 | Test |

Polynomial Ridge Regression achieved the highest held-out test R² among the models evaluated on test data.

## Key Takeaways

Living area, waterfront access and other property characteristics are useful predictors of house prices. Polynomial feature engineering can improve predictive performance, although model complexity and generalisation must be considered.

## Dataset and Attribution

King County House Sales dataset, originally published on Kaggle.

Project based on the IBM Skills Network *Data Analysis with Python* final assignment. Original course materials and attribution are retained in the notebook.

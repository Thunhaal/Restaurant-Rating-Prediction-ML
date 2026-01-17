# Restaurant Rating Prediction using Machine Learning

## Problem Statement
Predict the aggregate rating of restaurants based on cost, service availability, location, and user engagement metrics.

## Dataset
A restaurant dataset containing pricing, service features, location details, and user ratings.

## Approach
- Data cleaning and preprocessing
- Removal of unrated restaurants (rating = 0)
- Feature encoding
- Model training and comparison

## Models Used
- Linear Regression (Baseline)
- Decision Tree Regressor
- Random Forest Regressor (Final Model)

## Results
Random Forest achieved the best performance with:
- R² Score: 0.59
- Mean Squared Error: 0.125

## Key Insights
- User votes and pricing have the strongest influence on ratings.
- Tree-based models outperform linear models for this problem.

## Limitations
- Subjective nature of ratings
- Limited feature representation

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

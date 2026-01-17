# Restaurant Rating Prediction using Machine Learning

## Problem Statement
Develop a machine learning model to predict the aggregate rating of restaurants using features such as pricing, service availability, location, and user engagement metrics.

## Dataset
A real-world restaurant dataset containing information on pricing, service features, location details, and user-generated ratings.

## Methodology
- Data inspection and preprocessing
- Removal of unrated restaurants (aggregate rating = 0)
- Encoding of categorical features
- Train–test split and fair model comparison

## Models Implemented
- Linear Regression (Baseline)
- Decision Tree Regressor
- Random Forest Regressor (Final Model)

## Results
The Random Forest Regressor achieved the best performance:
- **R² Score:** 0.59  
- **Mean Squared Error:** 0.125  

## Key Insights
- User engagement (votes) and pricing-related features have the strongest influence on restaurant ratings.
- Tree-based ensemble models significantly outperform linear models for this prediction task.

## Limitations
- Restaurant ratings are subjective and influenced by factors not present in the dataset.
- Location information is encoded categorically and does not capture geographic proximity.

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

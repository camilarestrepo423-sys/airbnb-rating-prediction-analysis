# airbnb-rating-prediction-analysis
Machine learning and business analytics project analyzing Airbnb guest ratings.

## Overview

This project analyzes Airbnb listing data to identify the key drivers of guest satisfaction and predict whether a listing will receive a high rating.

Using Python, exploratory data analysis, Logistic Regression, and Random Forest models, the project evaluates how host characteristics, amenities, and listing features impact overall guest ratings.

## Key Results

- Analyzed 395 Airbnb listings
- Built Logistic Regression and Random Forest models
- Achieved ROC-AUC of 0.806
- Identified Superhost status and amenity count as strongest predictors of high ratings
- Generated actionable recommendations for Airbnb hosts

## Dataset

Source:
Inside Airbnb

395 rated Airbnb listings

## Research Questions

1. What listing and host characteristics are most associated with higher ratings?

2. Do higher-value listings receive higher ratings?

3. Which factors are controllable by hosts versus fixed factors?

## Methods

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Logistic Regression
- Random Forest Classification
- Model Evaluation
  - Accuracy
  - Precision
  - Recall
  - ROC-AUC

## Results

- Superhost status was the strongest predictor of high ratings.
- Amenity count showed the strongest numerical relationship with ratings.
- Cleanliness, communication, and listing accuracy were highly correlated with guest satisfaction.
- Logistic Regression achieved approximately 0.81 ROC-AUC.

## Technologies

- Python
- Pandas
- NumPy
- Random Forest
- Logistic Regresson
- Matplotlib
- Scikit-Learn
- Google Colab

## Files

- Airbnb Report.pdf
- airbnb_analysis.ipynb

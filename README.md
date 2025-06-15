# Zomato Analysis & Bulldozer Price Prediction

## Overview
This repository contains two projects I completed as part of my coursework:
- **Zomato Mini-Assignment:** Focused on cleaning and analyzing restaurant data from the Zomato dataset.
- **Bulldozer Price Prediction:** Built a machine learning model to estimate bulldozer sale prices at auctions.

Both projects helped me practice data cleaning, feature engineering, and predictive modeling using Python.

---

## Zomato Mini-Assignment
In this task:
- I explored the dataset, handled missing values, and standardized key columns.
- Extracted the primary cuisine for each restaurant.
- Grouped the data by cuisine to calculate average ratings, total votes, and average cost.
- Created simple visualizations to show top cuisines by rating and by popularity.

### Files
- `zomato_analysis.ipynb`: Notebook containing the full code and steps.
- `cleaned_zomato.csv`: Cleaned version of the dataset.
- `cuisine_summary.csv`: Grouped summary by cuisine.

---

## Bulldozer Price Prediction
In this project:
- I cleaned the data and handled missing values and incorrect types.
- Converted the sale date to datetime and extracted useful features (year, month, day).
- Encoded categorical columns.
- Trained a Random Forest Regressor model.
- Achieved a validation RMSLE of **0.2154** on my split of the data.
- Generated predictions on the test data in the required format.

### Files
- `bulldozer_prediction.ipynb`: Notebook with code and explanation.
- `test_predictions.csv`: Predictions generated for the test set.

---

## Tools Used
- Python (pandas, numpy, matplotlib, scikit-learn)
- Google Colab
- GitHub

---

## Notes
These projects were done as part of my learning. All work is original and focused on applying data science techniques to real datasets.

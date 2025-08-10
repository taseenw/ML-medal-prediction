# Olympic Medal Predictor

A machine learning project that predicts Olympic medal counts using linear regression. Built as my first ML project to learn the fundamentals of data science and predictive modeling. Gotta start somewhere

## What It Does

Predicts how many medals a country will win at the Olympics by analyzing team data like number of athletes, average age, and historical performance.

## The Process

1. **Data Exploration** - Analyzed correlations between features and medal counts
2. **Data Cleaning** - Removed missing values and filtered relevant columns  
3. **Train/Test Split** - Used pre-2012 data for training, 2012+ for testing
4. **Model Training** - Applied linear regression using scikit-learn
5. **Evaluation** - Calculated mean absolute error and analyzed results by country

## Key Insights

- Previous medal count is the strongest predictor (92% correlation)
- Model performs better for countries with higher medal counts
- Average prediction error: ~3.3 medals

## Tech

Python, pandas, scikit-learn, seaborn

## Files

- `olympic_medal_predictions.ipynb` - Main analysis and model
- `teams.csv` - Olympic team data
- `README.md` - This file

Built following a learning-focused approach to understand ML fundamentals.
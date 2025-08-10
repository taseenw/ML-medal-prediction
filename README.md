# Olympic Medal Predictor

A supervised machine learning project that predicts Olympic medal counts using linear regression. Built as my first ML project to learn the fundamentals of data science and predictive modeling. Gotta start somewhere

## What It Does

Predicts how many medals a country will win at the Olympics by analyzing team data like number of athletes, average age, and historical performance. Uses supervised learning to find patterns in historical Olympic data.

## The Process

1. **Data Exploration** - Analyzed correlations between features and medal counts
2. **Feature Selection** - Identified `prev_medals` and `athletes` as strongest predictors
3. **Data Cleaning** - Removed missing values and filtered relevant columns  
4. **Train/Test Split** - Used pre-2012 data for training, 2012+ for testing (temporal validation)
5. **Model Training** - Applied linear regression using scikit-learn
6. **Post-processing** - Handled negative predictions and rounded to whole numbers
7. **Evaluation** - Calculated mean absolute error and analyzed results by country

## Key Insights

- Previous medal count is the strongest predictor (92% correlation)
- Number of athletes sent correlates strongly with success (84% correlation)
- Model performs better for countries with higher medal counts
- Average prediction error: ~3.3 medals
- Countries like USA, France showed <5% error rates vs smaller nations with higher relative errors

## Tech Stack

- **Python** - Core programming language
- **pandas** - Data manipulation and analysis
- **scikit-learn** - Machine learning algorithms and metrics
- **seaborn** - Data visualization
- **NumPy** - Numerical computations

## Files

- `olympic_medal_predictions.ipynb` - Main analysis and model implementation
- `teams.csv` - Olympic team dataset with historical performance data
- `README.md` - This file

## Model Performance

- Mean Absolute Error: 3.30 medals
- Best predictions: High-performing countries (France: 2.2% error)
- Learning: Demonstrates the challenge of predicting rare events vs frequent outcomes

Built following a learning-focused approach to understand supervised ML fundamentals and the complete machine learning pipeline.
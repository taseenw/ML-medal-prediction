# Olympic Medal Predictor

Predicts Olympic medal counts using linear regression. My first ML project to learn the basics.

## How it works

Uses two main factors:
- Number of athletes a country sends
- Their previous Olympic performance

Trained on pre-2012 data, tested on 2012-2016 Olympics.

## Results

- Previous medals are the strongest predictor (92% correlation)
- Average error: ~3.3 medals
- Works better for countries that typically win more medals

## Built with

Python, pandas, scikit-learn, seaborn

## Files

- `olympic_medal_predictions.ipynb` - Main analysis
- `teams.csv` - Data
- `README.md` - This file

Basic linear regression to understand the ML workflow from data exploration to model evaluation.
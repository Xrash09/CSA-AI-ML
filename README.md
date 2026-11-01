# Planetary Devastation: Predicting Exoplanet Temperature

Predicting the equilibrium temperature of an exoplanet using linear regression built from scratch with only Pandas and NumPy.

## Data
NASA Exoplanet Archive, Planetary Systems Composite Parameters (PSCompPars). 6451 planets, 34 columns. The CSV (PSComp.csv) is included in this repo.

## What is done
- Data understanding and EDA (distributions, missing values, correlations)
- Preprocessing: log10 transform, 80/20 split, median fill, standardization
- Linear regression with the normal equation (NumPy only)
- Evaluation with MAE, RMSE and R^2 (also NumPy only)
- Hottest and coldest planet predictions
- Bonus: gradient descent check

## Results (test set)
MAE = 83.51 K, RMSE = 209.04 K, R^2 = 0.82

## How to run
1. Open `planetary_devastation.ipynb` in Google Colab or Jupyter.
2. Upload `PSComp.csv` and make sure the path in the first cells matches.
3. Run all cells.

## Files
- `planetary_devastation.ipynb`: the notebook, including the short report
- `PSComp.csv`: the dataset

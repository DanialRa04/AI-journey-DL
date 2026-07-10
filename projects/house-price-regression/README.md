# House Price Regression

Trying a simple Keras regression model on King County house sales data.

## Structure

- `codes/House_Price_Regression.ipynb` has the notebook
- `data/kc_house_data.csv` is the dataset used by the notebook

## Data note

The CSV is included because it is small enough for GitHub and needed to rerun the notebook.

## How to run

Open the notebook from the repo root, this project folder, or the `codes/` folder. The data path logic checks all three spots.

## Limitation

Training is set up for CPU-friendly runs with early stopping, so the exact stopping epoch can change a little across environments.

# Shale Oil and Gas Production Models

This project predicts total oil and gas production using Random Forest Regression models. The models use features such as:

- Months since January 2007
- Region
- Rig Count
- Production per Rig
- Legacy Production Change

## Project Structure

- `shale_production_model.ipynb` — Main Jupyter notebook with data analysis, modeling, and evaluation
- `data/Shale Raw Data.xlsx` — Raw input data

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- openpyxl

## Usage

1. Install the required packages:
    ```sh
    pip install pandas numpy matplotlib scikit-learn openpyxl
    ```
2. Open `shale_production_model.ipynb` in Jupyter or VS Code.
3. Run the notebook cells to load data, train models, and view results.

## Output

- Model evaluation metrics (score, mean absolute error)
- Feature importance plots
- Actual vs. predicted production plots
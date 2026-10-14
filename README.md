# INFOSYS722 — Iteration 4 BDAS

This project reproduces quarterly New Zealand Jobs Online AVI forecasting using Google Colab and PySpark.

## Data

- MBIE Jobs Online quarterly AVI dataset
- Stats NZ quarterly unemployment rate dataset

Both source files are included in `data/`.

## Technologies

- Google Colab
- PySpark DataFrame API
- PySpark MLlib
- Matplotlib, NumPy and pandas for visualisation

## Analysis

The notebook covers OSAS Steps 2–8, including data exploration, cleaning, integration, feature transformation, algorithm selection, model evaluation and iteration.

The model uses five historical AVI observations for 170 region-category series. Development-period validation is separate from the historical 2023–2025 evaluation.

## Running the notebook

1. Open the `.ipynb` file in Google Colab.
2. Install PySpark using the first code cell.
3. Make the two source CSV files available in the notebook's configured `DATA_DIR`.
4. Run the cells in order.

The notebook contains saved execution outputs, and the figures are also included in `figures/`.

## Evaluation limitation

The 2023–2025 evaluation period was examined in Iteration 3. It was not used to select the Iteration 4 model, but it is not a fully independent dataset across the wider project.

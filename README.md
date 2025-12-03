# Using Random Forest with Proportional Subsetting for Time Series Forecasting

This project was done as part of the Machine Learning class within my BS program at UCSB. It investigates the research by Hristos Tyralis and Georgia Papacharalampous on the use of Random Forest machine learning models for forecasting (https://www.mdpi.com/1999-4893/10/4/114), comparing them with contemporary procedures such as the Box-Jenkins methodology and Auto ARIMA.

### Overview
- Goal: Validate method feasibility and efficiency compared to standard practice.
- Stack: Python (SciKit-Learn, pmdarima), Jupyter notebook.

### Dataset
- Source: matthewjansen/bgc-jena-weather-station-dataset-20172024

### Methods
- EDA: data cleaning and descriptive analysis.
- Training: fit random forest with proportional lags, SARIMA, and AUTO ARIMA.
- Cross-validation: calculate MSE.

### Results (highlights)
- Cross-validated model MSE of 0.000034.
- Lowest MSE across all models.

### How to Run
1) Run `main.ipynb`

### Structure
- `data/`: BCG Jena Weather Station Dataset from 2017-2024.
- `notebooks/`: analysis notebook.

### Next
- Diversify models:
  * Introduce more models in cross-validation (e.g. Neural Networks).
  * Create a higher lag proportion parameter variety.
- Expand data scope to other, more complex time series.


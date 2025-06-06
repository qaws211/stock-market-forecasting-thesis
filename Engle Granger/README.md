# README - Engle Granger Folder

## Overview
This folder contains the core files for the analysis conducted in the thesis *"Stock Market Forecasting: An Extension of the Engle-Granger Approach"*. 
The objective of this study is to address the following research question: *'Is it possible to improve the predictive capability of the Engle-Granger model for the t+1 return of the S&P 500 index through the use of nonlinear models and ensemble learning techniques?'* 

## Main Files
### **Primary Analysis File**
- **`stock_market_forecasting_analysis.ipynb`** → This is the main analysis notebook. It:
  - Loads and preprocesses the dataset.
  - Implements the Engle-Granger two step approach for the cointegration analysis.
  - Applies machine learning and ensemble learning models.
  - Performs backtesting to evaluate predictive performance.

### **Dataset**
- **`shiller_data.xlsx`** → The primary dataset used for analysis. It contains financial monthly data including 10 years USA rates, earnings, and S&P 500 index values.

### **Supporting Notebooks**
- **`debug_forecast_regressors_construction.ipynb`** → Assists in debugging the "forecast_regressor_construction" function.
- **`debug_series_to_lagged.ipynb`** → Assists in debugging the "series_to_lagged" function. It lags the original data using the number of lags obtained in "var_lag_selection" function.
- **`debug_var_lag_selection.ipynb`** → Assists in debugging the "var_lag_selection" function. It Helps in selecting the optimal lag order for the VAR model at each iteration of the backtest cycle.
- **`lagged_matrix_example.xlsx`** → Example of how lagged matrices are constructed for modeling.

### **Results and Model Outputs**
- **`all_models_forecast_over_time_df.csv`** → Forecasted values from all models over time.
- **`models_weights_over_time_df.csv`** → Weights assigned to the forecast of each of the starting models to obtain the ensemble learning model "monthly weighted average bic"
- **`relative_forecast_residuals_df.csv`** →Relative residual errors of forecasts of each of the starting models.

## How to Run the Analysis
1. Open `stock_market_forecasting_analysis.ipynb` in **Jupyter Notebook** or **VS Code**.
2. Ensure all dependencies (e.g., `pandas`, `numpy`, `scikit-learn`, `statsmodels`, etc.) are installed.
3. Run the notebook step by step to:
   - Load `shiller_data.xlsx`.
   - Process the data.
   - Train models and evaluate results.

## Notes
- The `plots/` folder contains visualizations generated during analysis.
- Ensure that all necessary dependencies are installed before running the notebooks.
- This analysis is a **work in progress**, and improvements are continuously being made.

## Author
**Alberto Sartini**

## Contact
For any questions or collaborations, feel free to reach out:
- Email: sartinialberto1@outlook.it
- LinkedIn: www.linkedin.com/in/alberto-sartini-a78214296

---
**For more details on the project, refer to the main README in the repository.**

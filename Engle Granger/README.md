# README - Engle Granger Folder

## Overview
This folder contains the core files for the analysis conducted in the thesis *"Stock Market Forecasting: An Extension of the Engle-Granger Approach"*. 
The objective of this study is to address the following research question: *'Is it possible to improve the predictive capability of the Engle-Granger model for the t+1 return of the S&P 500 index through the use of nonlinear models and ensemble learning techniques?'* 

## Main Files
### **Primary Analysis File**
- **`Funzione_backtest_Variazione2.1.ipynb`** → This is the main analysis notebook. It:
  - Loads and preprocesses the dataset.
  - Implements the Engle-Granger two step approach for the cointegration analysis.
  - Applies machine learning and ensemble learning models.
  - Performs backtesting to evaluate predictive performance.

### **Dataset**
- **`SHILLER_Data.xlsx`** → The primary dataset used for analysis. It contains historical financial data including interest rates, earnings, and S&P 500 index values.

### **Supporting Notebooks**
- **`Debug_Calcolo_Forecast.ipynb`** → Assists in debugging forecast calculations.
- **`Debug_Series_To_Supervised.ipynb`** → Converts time series data into a supervised learning format.
- **`Debug_VAR_Lag_Selection.ipynb`** → Helps in selecting the optimal lag order for the VAR model.
- **`Esempio_Costruzione_Matrici_Ritardate.xlsx`** → Example of how lagged matrices are constructed for modeling.

### **Results and Model Outputs**
- **`all_models_forecast_over_time_df.csv`** → Forecasted values from all models over time.
- **`models_weights_over_time_df.csv`** → Model weight distributions over time.
- **`relative_forecast_residuals_df.csv`** → Residual errors of forecasts.

## How to Run the Analysis
1. Open `Funzione_backtest_Variazione2.1.ipynb` in **Jupyter Notebook** or **VS Code**.
2. Ensure all dependencies (e.g., `pandas`, `numpy`, `scikit-learn`, `statsmodels`, etc.) are installed.
3. Run the notebook step by step to:
   - Load `SHILLER_Data.xlsx`.
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

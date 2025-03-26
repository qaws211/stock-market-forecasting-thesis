# Stock Market Forecasting: An Extension of the Engle-Granger Approach  

## Thesis abstract  
This thesis explores the interaction between traditional econometric approaches and machine learning techniques in predictive analysis of stock markets. Specifically, it examines the relationship between the 10-year U.S. interest rate (10Y USA Rate), corporate earnings, and the S&P 500 index.  
The key research question addressed in this work is:  
**"Can the predictive performance of the Engle-Granger model on the S&P 500 index returns at t+1 be improved using machine learning and ensemble learning techniques?"**  

## Repository Structure  
This repository contains the following files:
- `LICENSE` - This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.  
- `Stock_market_forecasting_thesis_Alberto_Sartini.pdf` – Full thesis document 
- `Engle Granger/` –  Folder containing:
--  dataset used in the analysis.
--  Jupyter Notebooks with code implementation.
--  datasets containing the obtained results.
  further informations will be give in the README file inside this folder. 

## Technologies Used  
- **Python** 
- **Machine Learning Models** (random forest, support vector regression, artificial neural networks)  
- **Econometric Models** (Engle-Granger two-step cointegration analysis)  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `statsmodels`, `matplotlib`, `seaborn`, `tensorflow`, `keras`.   

## How to Use  
1. Clone or download this repository.
2. Open the folder `Engle Granger`
3. Open the file `Engle_Granger.code-workspace`
4. Use `Funzione_backtest_variazione_2.1.ipynb` to replicate the analysis

## Results & Findings  
- The **Engle-Granger two-step cointegration analysis** confirms the presence of a long-term relationship between the **10Y USA Rate**, **Earnings**, and the **S&P 500 index**.  
- Machine learning models, particularly **random forest and neural networks**, improve the predictive accuracy of short-term S&P 500 returns.  
- **Ensemble learning techniques** provide better generalization and reduce overfitting compared to single models.  
- **Feature selection and hyperparameter tuning** played a key role in enhancing model performance.  
- **Backtesting analysis** shows that the integration of econometric models with machine learning can be a valuable tool for financial forecasting.

## Work in Progress  
 **This project is still evolving!** 
I am currently working on:  
- **Improving model accuracy** by experimenting with additional feature engineering techniques.  
- **Expanding the dataset** to include additional macroeconomic indicators and alternative stock market indices.  
- **Enhancing backtesting strategies** to evaluate the robustness of the models in different market conditions.  

Stay tuned for future updates! 

## Author
**Alberto Sartini**

## Contact
For any questions or collaborations, feel free to reach out:
- Email: sartinialberto1@outlook.it
- LinkedIn: www.linkedin.com/in/alberto-sartini-a78214296

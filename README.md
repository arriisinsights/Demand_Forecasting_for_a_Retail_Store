
**Demand Forecasting for a Retail Store**

Project ID: *#CC69852*
Internship Domain: *Data Science Intern*
Organization: *CodeClause*
Author: *Aridweep Majumder, M.Tech*




*Project Overview*

This project aims to forecast retail product demand using time series forecasting methods. Accurate demand forecasting enables retailers to optimize inventory, reduce waste, and meet customer demand more efficiently.

The project uses historical sales data from a large Ecuadorian grocery retailer (Corporación Favorita), which includes daily sales records per product category and store. A Seasonal ARIMA (SARIMA) model was applied to identify time-based trends and patterns and to generate a future sales forecast.

The sales data was aggregated at the weekly level to reduce noise and better reflect seasonal patterns. Evaluation of the model's performance was conducted using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).




*Objective*

To develop a time series forecasting model using historical sales data

To understand seasonal and trend-based behaviors in retail demand

To generate demand forecasts for future weeks

To evaluate model accuracy using standard error metrics




*Dataset Description*

The dataset is publicly available and sourced from Kaggle's Store Sales - Time Series Forecasting competition.
Only the train.csv file was used in this project. It includes:

date: The date of the transaction

store_nbr: Store number

family: Product family or category

sales: Target variable (total sales)

onpromotion: Number of promotional items on that date


Other CSV files like test.csv, stores.csv, transactions.csv, holidays_events.csv, and oil.csv were excluded in this baseline project to keep the model focused on univariate forecasting.




*Technologies Used*

Python

Pandas

NumPy

Matplotlib

Statsmodels

Scikit-learn




*How to Run*

1. Clone the repository or download the notebook file.


2. Open the .ipynb file in Google Colab or Jupyter Notebook.


3. Upload the train.csv file from the original dataset to your environment.


4. Run all the cells in order to generate forecasts and visualizations.





*Results*

The SARIMA model successfully identified and forecasted weekly sales trends. While the error metrics (MAE and RMSE) are relatively high due to the scale of sales, the model captured seasonal behaviors effectively. Forecasts for the next 48 weeks were generated to demonstrate its use in planning future demand.




*Future Improvements*

Incorporating holiday and promotion data as external regressors

Building category-level or store-level forecasting models

Trying other time series models such as Prophet, XGBoost, or LSTM





*License*

This project is submitted as part of the CodeClause Data Science Internship.
For educational use only. No commercial redistribution or use of the original dataset is permitted without Kaggle’s consent.

# ARIMA
## Languages and Libraries
Language: Python
Libraries:
- numpy for numerical operations
- pandas for data manipulation
- matplotlib for data visualization
- statsmodels for time series analysis (ARIMA model, Augmented Dickey-Fuller test)
- itertools for combinatorial operations
## Data Analysis Methods
1. Data Loading and Exploration:
- Loaded the dataset from a CSV file.
- Displayed the first few rows, summary statistics, and data types.
2. Data Visualization:
- Plotted the time series of oil production volumes (bbl/day) to visualize trends over time.
3. Stationarity Check:
- Used the Augmented Dickey-Fuller (ADF) test to check for stationarity in the time series data. The high p-value (0.978) indicated non-stationarity.
4. Time Series Decomposition:
- Decomposed the time series into trend, seasonal, and residual components to understand underlying patterns.
5. ARIMA Modeling:  Applied the ARIMA (AutoRegressive Integrated Moving Average) model to forecast future oil production volumes. This involved:
- Differencing the data to achieve stationarity.
- Selecting optimal parameters (p, d, q) using grid search or AIC/BIC criteria.
- Fitting the model and generating forecasts.
## Key Findings
- The time series exhibits non-stationarity, requiring differencing for ARIMA modeling.
- The ARIMA model was used to capture trends and seasonality in the data, providing a foundation for forecasting future production volumes.
## How to Use
- Ensure all required libraries are installed (pip install numpy pandas matplotlib statsmodels).
- Load the dataset (COEBTM_set.csv) into the same directory as the notebook.
- Run the notebook cells sequentially to reproduce the analysis.

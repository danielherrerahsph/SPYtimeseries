# Time Series for S&P 500 Returns and Volatility Forecasting

This project forecasts returns and volatilities of the S&P 500 ETF Trust($SPY) using classical time series approaches such as ARMA, GARCH, and ARMA + GARCH, performing model diagnostics, and evaluating forecasts.

## Installation
**Python**
- arch
- matplotlib 
- numpy 
- pandas
- pmdarima
- scipy
- sklearn
- statsmodels
- yfinance

Open the terminal and run the following commands:
```
pip install arch matplotlib.pyplot numpy pandas pmdarima scipy sklearn statsmodels yfinance
```

**R**
- fGarch
- xts
- TSA
- rugarch

Open the R console and run the following commands:

```
install.packages("fGarch")
install.packages("xts")
install.packages("TSA")
install.packages("rugarch")
```
**Clone the Repository**

To clone this repository and access all the files, run the following command in your terminal:

```
git clone https://github.com/danielherrerahsph/SPYtimeseries.git
```

## Usage

To use the code, simply run either notebook in Jupyter Notebook or JupyterLab. The notebook contains step-by-step instructions for downloading the $SPY data, performing exploratory data analysis, building ARIMA models, performing model diagnostics, making forecasts, and evaluating the accuracy of the forecasts.

## Contributing

Contributions to this project are welcome. If you would like to report a bug or suggest a new feature, please open an issue on GitHub. If you would like to contribute code to the project, please fork the repository, make your changes, and submit a pull request.

## Credits

This project was created by Daniel Herrera. To read in more detail, check out my medium post [Part I: Introduction to ARMA Models with Financial Data](https://medium.com/@corredaniel1500/introduction-to-arma-models-with-financial-data-6ceb8b52fdd6)

## License
This project is licensed under the MIT License.



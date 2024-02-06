# SpyPredict

SpyPredict is a project aimed at predicting the daily closing price of the S&P 500 index (SPY) using machine learning techniques.

## Dependencies
- [yfinance](https://pypi.org/project/yfinance/): A Python library to fetch historical market data from Yahoo Finance.
- [tensorflow](https://www.tensorflow.org/): An open-source machine learning framework.
- [seaborn](https://seaborn.pydata.org/): A Python data visualization library based on matplotlib.
- [scikit-learn](https://scikit-learn.org/): A machine learning library for Python.

## Installation
You can install SpyPredict and its dependencies using pip:

```
pip install yfinance tensorflow seaborn scikit-learn
```

## Example (Work in Progress)
Below is a simple example of how to use SpyPredict:

```python
import yfinance as yf
from predict_spy_price import predict_price

# Fetch historical data
spy_data = yf.download('SPY')

# Predict closing price
predicted_price = predict_price(spy_data)

print("Predicted SPY closing price:", predicted_price)
```

## Acknowledgements
SpyPredict utilizes the power of machine learning and data analysis libraries. We acknowledge the contributors and maintainers of the following libraries:
- [yfinance](https://pypi.org/project/yfinance/)
- [tensorflow](https://www.tensorflow.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)

## Disclaimer
This project is for educational and informational purposes only. It should not be considered financial advice. Always do your own research and consult with a financial professional before making any investment decisions.

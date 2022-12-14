# stock_forecast

## Description 

This App uses Yahoo Fiance API, Prophet Model to predict trends on stock market. They are displayed on a WebApp using Streamlit and Plotly. 

## Disclaimer

This project was thought as a coding/ML exercise. The predictions depicted by the model shouldn't be used as a financial advise and should be considered cautiously; bevahiours of the market in the past are not proof nor signs of future behaviours. The developper doesn't aim at giving any investments adices and declines all responsability for the potential consequences of any investments made using this predictive model. 

## Requirements

* streamlit
* prophet
* yfinance
* plotly
* daal==2021.2.3
* numpy==1.22
* keyring==21.7
* urllib3==1.25

`pip install -r requirements.txt` can be used in the terminal after downloading this repository. 


## Illustrations

Situation of BEL20 Index from July to November 2022:

![BEL20](bel20_since07.png)

BEL20 Trend Prediction for the following months:
![BEL20_pred](bel_20_forecast.png)


## Demo

You can test this app on Streamlit [here](https://tonyanciaux-stock-forecast-main-c4i8yv.streamlit.app/)

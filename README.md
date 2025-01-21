# Tesla-Stock-Market_Linear-Regression
A Linear Regression model to implement and visualise the Stock Market trends.

Backend (app.py):
  1.Flask server setup
  2.Model loading and prediction logic
  3.Data preparation functions
  4.Real-time stock data fetching using yfinance
  5.RESTful endpoint for predictions

Frontend (index.html):
  1.Clean, responsive Bootstrap design
  2.Real-time prediction updates
  3.Loading states and error handling
  4.Visual indicators for price changes
  5.Last price and predicted price display


Tesla dataset: 
  1.Consists of  7 columns and  2193 rows.
  2.The dataset starts from 29-06-2010 to 15-03-2019.
  3.Open column, represents the price at which the stock started trading when market opened on the particular day.
  4.Close column, represents the price of individual stock, when the stock exchange closed the market for the day. It also represents the buy-sell order executed between two traders.
  5.High column, represents the highest price at which the stock traded during the period.
  6.Low column, Represents the lowest price at which the stock traded during the period.
  7.Volume column, indicates the total number of trading activity performed during a period of time.
  8.Adjacent column(Adj.), is a calculation adjustment made to the stock’s closing price. It is more complex and accurate than the closing price. The adjustment made to the closing price depicts the true price of the stock because the outside factors could have altered the True price.



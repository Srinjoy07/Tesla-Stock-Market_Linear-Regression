# Tesla-Stock-Market_Linear-Regression
A Linear Regression model to implement and visualise the Stock Market trends.

Backend (app.py):
<ul>
  Flask server setup
    Model loading and prediction logic
    Data preparation functions
    Real-time stock data fetching using yfinance
    RESTful endpoint for predictions
</ul>

Frontend (index.html):
<ul>
  Clean, responsive Bootstrap design
  Real-time prediction updates
  Loading states and error handling
  Visual indicators for price changes
  Last price and predicted price display
</ul>


Tesla dataset: 
<ul>
  Consists of  7 columns and  2193 rows.
 The dataset starts from 29-06-2010 to 15-03-2019.
 Open column, represents the price at which the stock started trading when market opened on the particular day.
 Close column, represents the price of individual stock, when the stock exchange closed the market for the day. It also represents the buy-sell order executed between two traders.
 High column, represents the highest price at which the stock traded during the period.
 Low column, Represents the lowest price at which the stock traded during the period.
 Volume column, indicates the total number of trading activity performed during a period of time.
 Adjacent column(Adj.), is a calculation adjustment made to the stock’s closing price. It is more complex and accurate than the closing price. The adjustment made to the closing price depicts the true price of the stock because the outside factors could have altered the True price.
</ul>


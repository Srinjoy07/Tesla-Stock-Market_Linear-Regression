# Tesla-Stock-Market_Linear-Regression
A Linear Regression model to implement and visualise the Stock Market trends.

Backend (app.py): <br>
  1.Flask server setup <br>
  2.Model loading and prediction logic <br>
  3.Data preparation functions <br>
  4.Real-time stock data fetching using yfinance <br>
  5.RESTful endpoint for predictions <br>
<br>
Frontend (index.html): <br>
  1.Clean, responsive Bootstrap design <br>
  2.Real-time prediction updates <br>
  3.Loading states and error handling <br>
  4.Visual indicators for price changes <br>
  5.Last price and predicted price display <br>
<br>
<br>
Tesla dataset: <br>
  1.Consists of  7 columns and  2193 rows.  <br>
  2.The dataset starts from 29-06-2010 to 15-03-2019.  <br>
  3.Open column, represents the price at which the stock started trading when market opened on the particular day. <br>
  4.Close column, represents the price of individual stock, when the stock exchange closed the market for the day. It also represents the buy-sell order executed between two traders. <br>
  5.High column, represents the highest price at which the stock traded during the period.  <br>
  6.Low column, Represents the lowest price at which the stock traded during the period.  <br>
  7.Volume column, indicates the total number of trading activity performed during a period of time.  <br>
  8.Adjacent column(Adj.), is a calculation adjustment made to the stock’s closing price. It is more complex and accurate than the closing price. The adjustment made to the closing price depicts the true price of the stock because the outside factors could have altered the True price.  <br>



# Google-Stock-Market-Prediction_Long-Short-Term-Memory
To visualize and analyze the Google stock price trends based on trained Long Short Term network.
<hr>
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
<hr>
<br>
Google dataset: <br>
<br>
A.Train Dataset: <br>
<pre>
  Consists of  6 columns and  1257 rows.
  The dataset starts from 03-01-2012 to 30-12-2016.
  Open column, represents the price at which the stock started trading when market opened on the particular day.
  Close column, represents the price of individual stock, when the stock exchange closed the market for the day. It also represents the buy-sell order executed 
  between two traders.
  High column, represents the highest price at which the stock traded during the period.
  Low column, Represents the lowest price at which the stock traded during the period.
  Volume column, indicates the total number of trading activity performed during a period of time.
</pre>
<br>
B.Test Dataset:
<pre>
  Consists of  6 columns and  251 rows.
  The dataset starts from 13-08-2018 to 13-08-2019.
  Open column, represents the price at which the stock started trading when market opened on the particular day.
  Close column, represents the price of individual stock, when the stock exchange closed the market for the day. It also represents the buy-sell order executed 
  between two traders.
  High column, represents the highest price at which the stock traded during the period.
  Low column, Represents the lowest price at which the stock traded during the period.
  Volume column, indicates the total number of trading activity performed during a period of time.
</pre>
  

  

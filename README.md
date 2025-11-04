# Yes Bank - Stock Closing Price Prediction ML

## Project Summary

Yes Bank is a banking company that was founded in 2004 that offers a wide range of differentiated products for its corporate and retail customers through retail banking and asset management services. It is also a publically traded company. That provides an opportunity for anyone to invest in Yes bank and become a shareholder. But at the same time, it means that the valuation of the company is now in the hands of investors and speculators as share prices are often heavily impacted by public opinion. We have used yes bank stock price data set. This dataset contains 5 different features that can be used for predicting close price prediction using machine learning. We have built machine learning regression model for price prediction. We have used some of best models.

## Objective

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month
Project Type - Linear Regression

## Dataset Overview

The dataset represents the historical stock data of Yes Bank. It contains 185 records with the following columns:

1. Date [Type: object (string)]
Represents the date on which the stock data was recorded. Format: "Month-Year" (e.g., "Jul-05", "Aug-05", etc.). This column is used to identify the time period for the respective stock data.

2. Open [Type: float64]
Represents the opening price of Yes Bank stock on the given date. This is the price of the stock when the market opens on that particular day. It is one of the key indicators of how the stock is performing on a specific day.

3. High [Type: float64]
Represents the highest price reached by Yes Bank stock during the trading day. This value indicates the peak price the stock reached within that trading day, showing the highest market valuation.

4. Low [Type: float64]
Represents the lowest price reached by Yes Bank stock during the trading day. This is the bottom price that the stock reached during that day's trading session. It shows the lowest valuation that the stock had during the trading day.

5. Close [Type: float64]
Represents the closing price of Yes Bank stock on the given date. This is the price of the stock when the market closes for the day. The closing price is one of the most important metrics for tracking the performance of a stock because it reflects the final market consensus of the stock's value for that day.

There are 185 datapoints in total, with the entire ranging from jul-05 to nov-20.The date column containing inapropriate datatype object which we need to convert in future for get trends and seasonal data accordingly , the columns Open, High,Low ,and Close are of float64 type, representing the numerical prices. In the data does not contains any null values



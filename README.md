# Yes Bank - Stock Closing Price Prediction ML

<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/db5cc92a-ffeb-4dd6-8562-61d61be54ff6" />

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

There are 185 datapoints in total, with the entire ranging from jul-05 to nov-20.The date column containing inapropriate datatype object which we need to convert in future for get trends and seasonal data accordingly , the columns Open, High,Low ,and Close are of float64 type, representing the numerical prices. In the data does not contains any null values.

<img width="948" height="533" alt="Image" src="https://github.com/user-attachments/assets/6818ad11-dba3-4cbe-bb33-e3c5bde23d6a" />

## Conclusion 

1) The dataset contains monthly stock prices of Yes Bank since its inception.
2) There is a significant impact on stock prices due to the fraud case involving Rana Kapoor in 2018.
3) No null values or duplicate data were found.
4) Despite outliers, they were retained to avoid data loss.
5) Applied power transformation to handle positively skewed distribution.
6) High correlation between dependent and independent variables indicates a good prediction potential.
7) High multicollinearity among independent variables due to small dataset.
8) KNN Regressor performed the best with an R2 score of 0.993115.
   
Project Utility for Stakeholders:

Accurate prediction of closing prices can assist investors in making informed decisions.
Helps in understanding the impact of major events on stock prices.
Provides a basis for further financial analysis and investment strategies.



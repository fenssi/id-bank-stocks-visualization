# Indonesia's Bank Stocks Visualization
Hi, this is my first self-exploratory project in the financial field to identify Indonesia Bank Stock visualization. The Indonesia Bank Stock Visualization project aims to provide a comprehensive analysis of historical stock data from major Indonesian banks. By focusing on key financial metrics, this project explores the patterns and relationships among bank stocks over time. Understanding these factors is crucial for investors and analysts looking to make informed decisions based on historical performance.

#❗️Disclaimer❗️
This project is intended for educational and analytical purposes. It shows the actual historical data of Indonesian Bank Stocks and doesn't serve as a recommendation or endorsement of any specific bank stock. The information provided here should not be interpreted as investment advice. Please conduct your own research or consult with a financial advisor before making any investment decisions.

## Objectives
1. The maximum and minimum closing price
2. Specific dates each bank stocks reach maximum and minimum return
3. Average return for each bank stocks
4. The most volatile and most stable based on standard deviation
5. Correlation between each pair of bank stocks and the level of strong relationships?

## Process
1. Install pandas-datareader and finance (Yahoo Finance)
2. Download bank stocks historical data
3. Maximum and minimum close price
4. Return calculation
5. Standard Deviation calculation
6. Create Pairplot visualization for correlation
7. Create Heatmap visualization for correlation
8. Create a close price trendline using Pyplot

## Summary
1. The range of maximum Close price from each of bank stock from 31 December 2013 to 31 December 2023 is 1,790 - 9,400. Meanwhile the minimum is 382 - 1,865
2. Most of the minimum and maximum returns of all the bank stocks are occurred in 2020
3. The highest return came from MEGA (0.094997%), but MEGA (0.027163) also has the highest of standard deviation value which it can be said that MEGA is the most volatile or riskiest
4. Based standard deviation, the lowest value of standard deviation is coming from BBCA (0.014471) which can be said that BBCA is the most stable, with the average of return is 0.073608%
5. To see the strength of correlation between each pair of bank stocks, we can see that BBCA shows a strong positive correlation with BBRI (0.97), MEGA (0.94), and BMRI (0.83) indicating that their prices tend to move together. But, Pairplot analysis reveals that the correlation with MEGA is less linear and more scattered compared to the more consistent linear relationships with BBRI, BMRI, and BBNI. This suggests that BBCA stock price movements are more predictably linked with BBRI, BMRI, and BBNI than with MEGA


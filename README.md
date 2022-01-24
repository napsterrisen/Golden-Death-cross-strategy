# Golden-cross-Death-cross
A golden cross suggests a long-term bull market going forward, while a death cross suggests a long-term bear market.

There is some variation of opinion as to precisely what constitutes this meaningful moving average crossover. Some analysts define it as a crossover of the 100-day moving average by the 50-day moving average; others define it as the crossover of the 200-day average by the 50-day average.


## Implementation:

Steps-----------------------------------------------------------------------------------------------------------------------------------------------------

Step 1: Fetched historical data of Bitcoin with yfinance library.

Step 2: Calculate the short term and long term rolling moving averages. (Note- I have taken a crossover of 100 day MA by 20 day MA in consideration)

Step 3: See the joining points. According to this strategy if recent average price gets more than long term average price then it creates a bullish signal and there is an uptrend suggesting to invest onto this particular stock. Look at the image below for the buy-sell signals

MA(20 days) | MA(100 days) | Bitcoin Historical data from Sep,2020 to Jan 2022 (+2 years)
![image](https://user-images.githubusercontent.com/73078264/150806878-37c60e44-8b74-4b0e-96ed-5d63f3797156.png)

## Insights:
Now suppose if a person bought a bitcoin on Oct 1, 2020

## Conclusion:


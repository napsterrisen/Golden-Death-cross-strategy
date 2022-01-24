# Golden-cross-Death-cross-Strategy
A golden cross suggests a long-term bull market going forward, while a death cross suggests a long-term bear market.

There is some variation of opinion as to precisely what constitutes this meaningful moving average crossover. Some analysts define it as a crossover of the 100-day moving average by the 50-day moving average; others define it as the crossover of the 200-day average by the 50-day average. (Note- I have taken a crossover of 100 day MA by 20 day MA in consideration)


## Implementation:

Steps---------------------------------------------------------------------------------------------------------

Step 1: Fetched historical data of Bitcoin with yfinance library.

Step 2: Calculated the short term and long term rolling moving averages. 

Step 3: According to this strategy if recent average price gets more than long term average price then it creates a bullish signal and there is an uptrend suggesting to invest onto this particular stock. Look at the image below for the buy-sell signals

Bitcoin Historical data from Sep,2020 to Jan 2022 (+2 years)
![image](https://user-images.githubusercontent.com/73078264/150806878-37c60e44-8b74-4b0e-96ed-5d63f3797156.png)

## Insights:
Now suppose if a person bought a bitcoin on Oct 1, 2020 at closing price of 10.53k and sells it after 2 years at 33.4k

Total gain on investment = 22.86k
, ROI                      = 217.18%

If we go with the Golden-Death cross strategy, we will be doing two swings as shown in the image above:

First swing: 43.5k-10.53k = 32.97k

Second swing: 47.24k-45.5k = 1.74k

Total gain on investment = 34.71k  + saving a loss of -13.84k (33.4k-47.24k) by exiting at earlier stage, ROI                      = 329.62%


## Conclusion:
By using this strategy we would have made a 330% return in 2 years which is 100% more as compared to bitcoin price volatility. As we all can see that crypto is crashing like hell, this startegy could have saved us by giving an exit signal and thus saving 13.84k $ in current situation.
 
To summarize, A golden cross occurs when a short-term MA crosses above a long term MA. A death cross occurs when a short term MA crosses below a long term MA. They can both be used as reliable tools for confirming long-term trend reversals in the stock market, forex, or cryptocurrency.

# Defensive Stock Analysis
by: Armun Shakeri

### Overview and Business Problem

During times of uncertainty investors want to protect their assets from loss. For this porject we will analyze 3 consumer defensive stocks by performing time series analysis (SARIMA models) and linear regression. By doing so we will try to forecast stock prices in the near future. We will choose the 3 stocks based on highest market caps. The main questions we will be asking are do defensive stocks protect against market volatility? If so should you buy or sell the top 3 market weighted defensive stocks. This analysis is for educational purposes only and does not represent any investment recommendations.


### Data

The data acquired for this project represents broad market data including, S&P 500, stocks within the S&P500, Etherum, PPI (producer price index), Dollar index, and gold rates.

The final merged dataset (df4) has 190 columns and contains 8 columns:
Date: Date of close
Symbol: Symbol of defensive stock
Close: Close price of defensive stock
SPClose: Close Price of S&P 500
Gold: Gold Price
Ether: Ethereum Price
USD: US dollar index
PPI: Producer Price Index

### Methods and Analysis



### Conclusion

After analysis of the top three defensive stocks, determined by market cap, there were patterns that were observed. The main pattern observed was that defensive stocks did provide protection against market volatility. Based on these observations the recommendations go as follows:


1) Walmart showed to have an downward trend, hold or sell WMT.


2) KO showed to have an upward trend, buy KO.


3) PG showed a bearish trend, buy PG.


### Next Steps

1) This project focused mainly on recent market data, beginning in 2017. This created issues when trying to identify an accurate trend. For more accurate results we will gather information about the markets at an earlier date, starting preferably at 2010.

2) We will include other indicies such as the VIX, NASDAQ, and Dow Jones to provide a wider market perspective to see how defensive stocks hedge against moves in the broader market.


## Repository Structure

├── Data
├── Images
├── Analysis.ipynb
├── Presentation4.pdf 
├── README.md 
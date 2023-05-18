# **Big Tech Stock Market Performance**

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/Big_tech.jpg?raw=true)

**Data Set Information:**

Use real time data from Yahoo Finance API or dataset stored in "Data".

The 5 big tech to analyze are:
* Google(GOOG)
* Amazon(AMZN)
* Apple(AAPL)
* Meta(META)
* Microsoft(MSFT)

**Attribute Information:**

* Ticker:type of stock symbol that describes information about the stock of a company.
* Date: stock market date.
* Open:the price when the market opened in the morning.
* High:the highest price during that trading day.
* Low:the lowest price during that trading day.
* Close:the price when the market closed in the afternoon.
* Adj Close (Adjusted Close) :a price adjusted to make prices comparable over time
* Volume:number of shares of the stock traded that day.

**Target:**
Utilize Python to analyze the historical performance of various Big Tech companies, accurately identify potential opportunities and risks in the stock market, and provide informed recommendations for investment strategies.

## Real Time Dataset

```
  Ticker       Date       Open       High        Low      Close  Adj Close   
0   GOOG 2022-11-18  99.010002  99.160004  96.739998  97.800003  97.800003  \
1   GOOG 2022-11-21  97.559998  98.720001  95.669998  95.830002  95.830002   
2   GOOG 2022-11-22  96.160004  97.547997  94.410004  97.330002  97.330002   
3   GOOG 2022-11-23  97.339996  99.069000  97.339996  98.820000  98.820000   
4   GOOG 2022-11-25  98.464996  98.940002  97.529999  97.599998  97.599998   

     Volume  
0  24969900  
1  18696900  
2  18868900  
3  17568900  
4   8567800  
```

## Stock Market Performance (Last 6 Months)

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/st_mk_perf.png?raw=true)

* Apparently, Microsoft (MSFT) and Meta (META) have higher Stock Market Performance.


## Stock Prices (All companies)

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/st_pr_comp.png?raw=true)

* All Big Tech Companies show an increasing Stock prices.

## Moving averages (Meta and Microsoft)

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/META_mov_averg.png?raw=true)

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/MSFT_mov_averg.png?raw=true)

* When the MA10 crosses above the MA20, it is considered a bullish signal indicating that the stock price will continue to rise. Conversely, when the MA10 crosses below the MA20, it is a bearish signal that the stock price will continue falling.

## Volatility:

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/volatility.png?raw=true)

* High volatility indicates that the stock or market experiences large and frequent price movements, while low volatility indicates that the market experiences smaller or less frequent price movements. Meta had a high volatility during Feb-2023 and recently May-2023.

## Correlation between Meta and Microsoft:

![alt text](https://github.com/Cristhian-Ninanya/Big_Tech_Stock_Market/blob/main/images/corr_META_MSFT.png?raw=true)

**Observations:**

* There is a interesting linear relationship between the stock prices of Meta and Microsoft, which means that when the stock price of Meta increases, the stock price of Microsoft also tends to increase. 

* It is a sign of a strong correlation or similarity between the two companies, which can be due to factors such as industry trends, market conditions, or common business partners or customers. 

* For investors, this positive correlation may indicate an opportunity to diversify their portfolio by investing in both companies, as both stocks may offer similar potential returns and risks..

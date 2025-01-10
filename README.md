# ArbiSweep
Arbisweep Version One is a an iPython Notebook File with seven base technical/fundamental indicators that will help the average retail investing market participant have a fundamental baseline for portfolio allocation strategies across "The Big Three" market classes. This was completed as a capstone project for Imperial College London's 2024 MSc in Financial Technology course. However, this project has been continuously iterated upon:

Since the days of the barter system, the importance of individual custodianship over ones assets has arguably never been more important in society. 

This holds true across many global markets. However, the three key motivating markets of interest and “high-ceiling” growth potential for the purposes of Arbisweep include: 

*	New York Stock Exchange Markets 
*	USA Real Estate Market
*	Decentralized Finance (DeFi)/Crypto-Based Asset Markets 


* Decision points are needed to inform and enact investment strategies in new and emerging markets such as DeFi.
* An understanding of fundamentals lower the barrier of entry for individual portfolio management and responsible stewardship of one’s assets.
* Arbisweep is not intended to be a substitute for traditional financial advisory services, rather an extra set of “data points” for the average retail investor to evaluate micro/macroeconomic landscape.

## Arbisweep Version One Indicator List

1.	The S&P 500 Level
2.	The Current 30-Year Fixed USA Mortgage Rate
3.	The Bitcoin Level
4.	The S&P 500 Sharpe Ratio
5.	The Bitcoin Sharpe Ratio
6.	The Median price of homes in the USA
7.	Asset “Volume Checker”

## Technical Indicator Insights:

# S&P 500 Level

The S&P 500 is a collection of the 500 most important companies on the New York Stock Exchange. The Arbisweep output includes the following:
*	‘Open’: Opening value at market start (9:00 AM EST on previous calendar date)
*	‘Close’: Closing value at market end (5:00 PM EST on previous calendar date)
*	‘High’: Maximum value on previous calendar date
*	‘Low’: Minimum value on previous calendar date
*	‘Volume’: Quantity of outstanding shares traded on the day, using the $SPY ETF as a proxy for the S&P 500 Portfolio with Alpha Vantage API

# The Current 30-Year Fixed USA Mortgage Rate

Mortgage rates are important for retail investors to keep up with when it comes to timing home purchases. This is an indicator that any homeowner should have insight to before purchasing. The 30-Year Fixed USA Mortgage Rate is a direct reflection of inflation, economic trajectory, Federal reserve perspectives, the bond market, and general housing conditions from a supply and demand point of view as shared by Investopedia (2024).

This indicator was pulled via the Requests and the BeautifulSoup4 packages respectively and BankRate.com as a benchmark reference

# The Bitcoin Level

As the Cryptocurrency/Decentralized Finance markets continue to grow, the price movement of Bitcoin has become increasingly effective in determining where the market is trending. This is important for any retail investor in the space to understand.

# The Sharpe Ratio ($SPY and $BTC)

The Sharpe Ratio is a systemic measure of risk for any asset. It generally lets consumers know when an asset is risk-on or risk-off by assessing the “expected differential return and the associated risk” (Sharpe, 1994).  This indicator was pulled via the Requests and the BeautifulSoup4 packages respectively and PortfoliosLab.com as a benchmark reference. 


Sharpe Ratio =  (R_asset-R_f)/(Standard Deviation of Asset )

	R_asset = Return of Asset
	R_f = Risk Free Rate of Asset
	Standard Deviation is made in reference to the differential return mentioned above

# The Median price of homes in the USA

This indicator is a bit more intuitive for retail investors and can be used best in tandem with the 30-Year Fixed USA Mortgage Rate indicator above. This indicator was pulled via Requests and the BeautifulSoup4 packages respectively and Ycharts.com as a benchmark reference

# The Volume Checker

As mentioned above, the volume traded on an asset represents the quantity of outstanding shares traded on the day. Arbisweep allows users to search for the volume of tickers on the NYSE. This is currently a static and manual check that will be improved and visualized within future iterations of Arbisweep. The output below is tested on the following NYSE tickers: $AAPL, $AMZN, $V, $MSFT, $GOOGL, $JNJ, $PG, $JPM, and $BRK.



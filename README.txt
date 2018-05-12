Source files not attached as requested by the professor.
This project consists of 1 module, and 4 programs using it for different needs.
Further files explanation ahead.

------------------------------------------------------------------------------
stocksinfo
========== 

Module used for collecting, saving, and analysing past stock prices.

------------------------------------------------------------------------------
daily_change
============

Input :		- Date
		- List of stocks tickers

Output:	For each stock:
		- Closing price for on that date
		- Profitability change from the day before

------------------------------------------------------------------------------
create_file
===========

Input:		- Start date
		- End date
		- Ticker name
		- Name (or path/name)
		- Format (CSV / JSON)

Output:		- File containing all the stock data in the requested time range.

------------------------------------------------------------------------------
compare_stocks
===============

Input:		- Start date
		- End date 
		- List of stocks tickers

Output:		- Table with data summary for each stock. Columns:
	 	 ticker name, accumulated profit, peak to valley value, highest,
 	 	 lowest, average, mean prices for requested time range.
------------------------------------------------------------------------------
index_graph
===============

Input:		- Start date
		- End date 
		- List of stocks tickers
		- One index between: price, daily profit change, accumulated profit,
                                            minimum price, maximum price.

Output: 	- Graph for the requested time range, comparing the selected index
	  	for all the stocks in the list.
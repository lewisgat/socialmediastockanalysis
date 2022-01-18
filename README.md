# Social Media Stock Analysis

This project is a simple attempt to look at the relationship between a stocks performance and social media discussion. 

# How to use
Ticker Mention Puller.ipynb is used to pull the tickers that are mentioned and the number of times they are mentioned. By default it is collecting weekly data from Nov 2020 to Nov 2021. One file that was outputted from it is TickerPullsAbove20Mentions.csv, which contains all the tickers mentioned more than 20 times in each week.

Obtain Ticker Returns.ipynb takes one of the outputted csv's from the previous python file and obtains the weekly returns for those tickers. These will be used in the last file.
The outputted file from this is 'df_with_returns.csv'

Correlation Analysis and Portfolio Calculation.ipynb takes this outputted file and uses it to calculate the returns of a portfolio of equally weighted stocks that have a high number of mentions. 

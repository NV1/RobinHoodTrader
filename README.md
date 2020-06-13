# Robinhood RSI Trader Bot v1.20

An effective python based fully automated trading system for the beginner trader who is stepping into the algo trading industry with low volume assests. This trader bot utilizes one of the most popular stock brokerage in the current generation, Robinhood. The stable system lays the foundation for algorithmic trading and the connection between Python and the Stocks Industry.

The official Robinhood API is private, so an unoffical Robinhood API scraped and maintained by a widespread community is imported. The RSI momentum indicator is implemented to buy <= 30 and sell >= 70. It lays the foundation for the algorithm and for a scheduler to continuesly check by minute to minute basis for new price changes. 

Disclaimers:
The Bot provides a basic architecture for algorithmic trading and is not meant to be deployed into a production line. Individual's Robinhood username and passwords are NOT saved or logged into cloud databases. 



Robinhood Trader Bot v1.00
The Trader Bot was given a Robinhood account with $50 and after 1 day the portfolio increased by 0.06%. 

Updates:
Due to the RSI system (buy  <= 30 and  sell >= 70), the reversal entry point (buy <= 30) noticed inefficiencies and increased risk.
-Added an additional layer support and resistance to increase security in the position at accurate reversal point

Robinhood Trader Bot v1.20
The Trader Bot at 11:19AM bought Ford Stock (1 share at $6.29) and sold at 12:08PM for 1 share at $6.34 per share. $0.05 per share were made in that timeframe, with a portfolio increase by 1%.

Updates in Progress:
-Implementation of backtesting for long term trading 
-Addition of autodrawing system
-Increase layer of support an resistance lines
-RSI momentum on graphical chart

How To Run:
-Download Repo as clone (zip file)
-Open project on IDE (PyCharm, Visual Studio, etc...)
-Install missing packages and to install Robinhood package go to (https://pypi.org/project/robin-stocks/)
-Run and sign in with Robinhood username and password  (Two-Factor Sign In is required)
-Enjoy!


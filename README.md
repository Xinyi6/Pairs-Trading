# Pairs-Trading
A Statistical Arbitrage Strategy
Pairs trading is a market-neutral trading strategy that matches a long position with a short position in a pair of
highly correlated instruments such as two stocks, exchange-traded funds, currencies, commodities or options.
Pairs traders wait for weakness in the correlation and then go long the under-performer while simultaneously
short selling the over-performer, closing the positions as the relationship returns to statistical norms. In this paper,
we utilized three different strategies (minimum distance, co-integration and copula) to perform pairs trading
from pair selection to signal capture.
The data in this paper contains the close prices of the S&P 500 stocks from Yahoo. Finance in the period of
2013-2018. These stocks are among the most liquid in the world. Consequently, transaction costs will be
relatively low considering the time and effort of completing a transaction. According to the assumptions and the
characteristics of the three methods, we used different train and test datasets. For minimum distance method, we
trained all the data from 2017, and tested on the data from Jan 2018 to Apr 2018; For co-integration method, the
training dataset is from Jan 2017 to Oct 2017 and the testing dataset is from the latter two months; For copula
method, we divided data into training set from 2013 to 2016 and test set from 2017 to 2018.

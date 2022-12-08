# Week_3_Challenge
Week 3 Challenge Assignment

# Arbitrage Profits between crypto exchanges
In this assignment we look at the price of bitcoin on two seperate exchanges over time to see if arbitrage profits are both profitable and consistent.
To accomplish we will need to import pandas and read the data on the csv files for both the bitstamp and coinbase exchanges. 
First we will clean the data for both exchanges to make it usable in our analysis. We will accomplish this by formatting the dates, dropping all NaN
values, and removing the dollar signs. Next we will convert the data type from the column containing the dollar sign from a string to a floating value so that we can use it mathematically. Finally we will drop all duplicate values from our data set. 
Once the data is cleaned and ready for use we will get summary statics for each exchange and begin comparing their values over time. We are looking for differences in the price of bitcoin between the two exchanges and if a difference is found, does it continue as time goes on. 
If a difference in price occurs between the exchanges then it is possible to earn a profit by buying bitcoin on the exchange with the lower price and selling it on the exchange with the higher price for a riskless profit until the markets have reached an equilibrium. 

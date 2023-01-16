# Historical VaR

## Discription  
This repository represents how to calculate VaR using Historical Method on Python.

We will need the following Libraries that will need to be imported.

1. pandas
2. numpy
3. datetime
4. pandas_datareader
5. scipy
6. matplotlib
7. yfinance


This program is implemented in [Python 3.7](https://www.python.org/downloads/release/python-377/). 

### Introduction:

Value at Risk (VaR) is a financial metric that estimates the risk of an investment. More specifically, VaR is a statistical technique used to measure the amount of potential loss that could happen in an investment portfolio over a specified period of time. Value at Risk gives the probability of losing more than a given amount in a given portfolio.

Value at Risk is applicable to all types of assets – bonds, shares, derivatives, currencies, etc. Thus, VaR can be easily used by different banks and financial institutions to assess the profitability and risk of different investments, and allocate risk based on VaR

The historical method simply re-organizes actual historical returns, putting them in order from worst to best. It then assumes that history will repeat itself, from a risk perspective. 

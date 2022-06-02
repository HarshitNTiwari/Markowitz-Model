# Markowitz-Model
This project is a Python implementation of Markowitz's Portfolio Optimization Model. 
The aim is to create a portfolio containing stocks of the FAANG companies: FB, AAPL, AMZN, NFLX, GOOG.

The portfolio is to be optimised in such a way that highest return is achieved for a given risk. 

The historical data of the stock prices for the last 10 years is fetched from [Yahoo! Finance](https://finance.yahoo.com/) using the yFinance library. The data looks as follows:

The comparative chart of the stock prices of the five companies is as follows:

![chart](https://github.com/HarshitNTiwari/Markowitz-Model/blob/main/assets/comparitive_stock_price_chart.png)

In order to create the most efficient portfolio, first 10000 different random portfolios are made and are plotted on a Returns Vs Risk plot. 
Each circle in the plot below represents a portfolio. The portfolios towards the upper left side of the plot (yellowish circles) are the more efficient ones as they provide more returns for lesser risk.

![Plot 1](https://github.com/HarshitNTiwari/Markowitz-Model/blob/main/assets/Return_vs_Risk_1.png)

Among these 10000 portfolios, the one with the highest returns-to-risk ratio is the most efficient portfolio. It is marked with a green star in the plot below:

![Plot 2](https://github.com/HarshitNTiwari/Markowitz-Model/blob/main/assets/Return_vs_Risk_2.png)

The weights for this optimal portfolio are : [0.046  0.451  0.267  0.081   0.154].

The above results suggest[^1] that according to the data of last one decade, an optimal portfolio diversification among the FAANG companies would be something like: 4.6% in FB, 45.1% in AAPL, 26.7% in AMZN, 8.1% in NFLX and 15.4% in GOOG. At this distribution, you can achieve 25% annual returns at 23% risk with best return-to-risk ratio being 1.07

[^1]: Not meant as an actual financial advice!


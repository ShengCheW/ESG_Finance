# ESG_Finance
Financial Engineering for ESG Finance by Professor Cyril Shmatov

Session 1 HW:
Which name in the S&P 500 currently has the best Environmental score? Worst Environmental score?

1. yfinance can't work, so I use yahooquery[https://pypi.org/project/yahooquery/1.1.0/]
2. Scrape the S&P 500 tickers from the Wikipedia page[https://en.wikipedia.org/wiki/List_of_S%26P_500_companies]
3. Getting environmentScore
4. Find the best and worst

Session 2HW:
How does the time series of the low-vol index derived in class for Pharma compare to (a) equal-weighted Pharma index? (b) price-weighted Pharma index? (plot three series together)

1. For the equal-weighted index, I simply assign equal weights to all stocks in the portfolio and calculate the cumulative return series
2. For the price-weighted index, I determine the weights based on the most recent prices and calculate the cumulative return series
3. Then plot all three series (low volatility, equal-weighted, and price-weighted) together on the same graph to visualize and compare their performances over time


Session 4 HW:
Based on Alternative text data class session:
We have extracted the most common bigrams (by TF-IDF) in the ESG Reports corpus.

1. What are the three most common bigrams by TF alone?
2. What are the three most common bigrams (by TF-IDF) among the reports by (only) large banks?

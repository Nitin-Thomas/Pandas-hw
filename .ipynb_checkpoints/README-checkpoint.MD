# Unit 4 Homework Assignment: A Whale Off the Port(folio)

Harold's company has been investing in algorithmic trading strategies. Some of the investment managers love them, some hate them, but they all think their way is best.

I just learned these quantitative analysis techniques with Python and Pandas, so Harold has came to me with a challenge to help him determine which portfolio is performing the best across multiple areas: volatility, returns, risk, and Sharpe ratios.

I created a tool (an analysis notebook) that analyzes and visualizes the major metrics of the portfolios across all of these areas, to determine which portfolio outperformed the others. I've taken historical daily returns of several portfolios, some from the firm's algorithmic portfolios, some that represent the portfolios of famous "whale" investors like Warren Buffett, and some from the big hedge and mutual funds. I then used this analysis to create a custom portfolio of stocks to compare its performance to that of the other portfolios, as well as the larger market S&P TSX 60 Index.

Harold was ecstatic that I was able to help him prove that the algorithmic trading portfolios are doing so well compared to the market and whales portfolios. However, taking it forward one step, I wondered whether I can choose my own portfolio and test whether it can performs just as well as the algorithmic portfolios. 

I picked three preferred stocks and ran the same analysis. The custom portfolio represented by the stock returns of Loblaws(L), Open Text Corp(OTEX) and Shopify(SHOP), with its returns weighted equally, and had the following observations...

The Custom Portfolio shows a low correlation with all the other portfolios, and a weak but positive correlation with the S&P TSX 60.

In terms of Volatility, the Custom Portfolio has one of the lesser volatilities compared to the others, except the S&P TSX 60, Algo 1 and Paulson. In other words, the Custom Portfolio is more riskier than the S&P TSX 60. Clearly, Harold's Algorithmic Trading Model 1 outperforms other portfolios, as well as my own.

The Custom Portfolio's beta with the S&P TSX 60 ranges between 0.4 - 0.7  through the year, with the mean of the beta close to 0.5, suggesting that the volatility of the portfolio with the TSX is almost  correlated with the market. 

When considering the Sharpe Ratio, the Custom Portfolio delivers a market beating performance, but the performance is lower all other portfolios except the Paulson Fund and the Tiger Global Fund. 

To summarize, the Custom Portfolio holds more risk per unit of return compared to the S&P TSX 60. However, it is possible that this performance is skewed towards the performance in 2019, as the underlying data bounds the data only to 2019. In the previous section of this, the Sharpe Ratios of the other portfolios were quite positive over a wider period of time, and significantly INVERSE when considering 2018. It is fair to say that the Custom Portfolio performed well, but beat only two portfolios...but Harold's portfolio did significantly better than mine.
# Stock-market
This project leverages unsupervised learning techniques to develop a trading strategy aimed at outperforming the S&P 500 index. Key steps include:

**Data Collection:**

Downloaded historical price data for S&P 500 stocks using yfinance and filtered the top 150 most liquid stocks based on trading volume.

**Feature Engineering:**

Calculated various technical indicators and returns for multiple time horizons.
Incorporated systematic risk factors using Fama-French models and rolling regression to estimate factor betas.

**Clustering:**

Applied K-Means clustering monthly to group stocks based on features like returns, volatility, liquidity, and factor exposures.

**Portfolio Optimization:**

Constructed an optimized portfolio using the Efficient Frontier to maximize the Sharpe Ratio, selecting stocks from clusters with favorable risk-reward profiles.

**Performance Analysis:**

Visualized portfolio returns and compared them against the S&P 500 benchmark, demonstrating significant potential for superior returns.

**Technologies Used:**

Python libraries: pandas, numpy, matplotlib, statsmodels, yfinance, scikit-learn, PyPortfolioOpt.


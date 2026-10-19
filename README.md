Portfolio Optimiser

Built an interactive Portfolio Optimiser that applies Modern Portfolio Theory and Monte Carlo simulation to find the best asset allocation for a user-defined portfolio. Users enter their holdings by ticker, and the tool pulls historical prices live from the Financial Modeling Prep (FMP) API. It then builds four portfolios: Maximum Sharpe Ratio, Minimum Variance, Highest Realised Return and an Equal Weight baseline. Every holding is kept between 1% and 30% so each portfolio stays diversified. The dashboard plots the risk and return of 4,000 simulated portfolios against the best achievable trade-off. It benchmarks performance against the S&P 500 using cumulative growth, drawdowns, rolling Sharpe ratios, beta and correlation. Developed in HTML, CSS and JavaScript, with all optimisation running in the browser and interactive charts built with Chart.js.

Data Requirements

No file upload is needed. Daily price history is fetched automatically from FMP for each ticker entered, along with the S&P 500 as a benchmark. Dividend-adjusted prices are used where the API plan allows. Portfolios can hold 2 to 50 assets, with 1, 2, 3 or 5 years of history.

How to Use

Open the dashboard in a web browser.
Enter the tickers in your portfolio, for example AAPL, MSFT, NVDA, or click “Use example portfolio”.
Choose the length of price history and set the annual risk-free rate.
Click “Optimise portfolio”.
Review the results across three tabs:
Risk / Return & Weights: the recommended weights for each portfolio.
Comparison: performance against the S&P 500.
Correlation: how closely the holdings move together, and the diversification this gives.

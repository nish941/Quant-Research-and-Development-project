Project Overview:

Analyze a primary company and construct two portfolios using Python, utilizing the yfinance library for data retrieval.The analysis will involve data manipulation, statistical calculations, and financial modeling.Interpret the results and provide insights based on the findings.

Companies -  
Take any 5 companies starting with letter "n" . Choosing one of the companies as your primary company.

I. Market Analysis

a. Historical Price Movement Analysis

Use Python with yfinance to fetch and process historical daily price data for the primary company for the last 5 years.
Implement functions to calculate and visualize:
Price charts (daily, weekly, monthly)
Lifetime high and low
52-week high and low
Risk measures (standard deviation, beta)
Return measures (daily, monthly, annual returns)
Technical indicators:
Moving Averages (20-day and 50-day)
RSI (14-day)
MACD (12-day, 26-day, 9-day signal)
Analyze the changing nature of risk parameters over time.

b. Ratio Analysis

Implement functions to calculate and analyze key financial ratios for the most recent fiscal year:
Valuation ratios (P/E, P/B, EV/EBITDA)
Profitability ratios (ROE, ROA, Profit Margin)
Growth parameters (Revenue growth, EPS growth)
Cash flow parameters (FCF, Cash Conversion Cycle)
Working capital management (Current Ratio, Quick Ratio)
Compare the stock price performance with the firm's financial performance.
Provide a detailed explanation of any congruence or deviation observed between price performance and financial performance. Also explain the significance of any 5 ratios. 


II. Portfolio Analysis

a. Portfolio Construction and Evaluation

Implement a function to construct a portfolio of 5 stocks:
30% investment in the primary company
Price-weighted for the remaining 4 stocks
Develop functions to calculate portfolio metrics using daily data for the last 3 years:
Sharpe ratio
Treynor ratio
Jensen's Alpha
Compare the portfolio's performance with a benchmark index over the last three years.
Analyze portfolio performance for each individual year.
Explain the reasons for any deviation between index returns and portfolio returns.

b. Single Stock vs. Portfolio Comparison

Implement functions to compare the risk-reward pattern of the primary stock against the portfolio using daily data for the last 3 years.
Use statistical measures to evaluate the benefits of diversification.

c. Correlation-based Portfolio

Develop a function to create a correlation matrix for the selected stocks using daily data for the last 3 years.
Implement an algorithm to construct a new portfolio based on correlation parameters:
30% investment in the primary stock
Remaining weights based on correlation with the primary company and ranked price-weights from part a.
Compare the performance of this correlation-based portfolio with the price-weighted portfolio and explain any possible findings or reasons.



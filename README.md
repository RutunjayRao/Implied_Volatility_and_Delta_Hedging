# Implied_Volatility_and_Delta_Hedging
Forecasting a stock's volatility by calculating its implied volatility and creating a delta-neural portfolio.

We'll calculate implied volatility for a point in the future using the Black-Scholes model to back-calculate the volatility(sigma) based on the market price of a put option. The portfolio is delta-neutral because price decreases are wholly offset by a complementary increase in the put options. We will also observe its option price sensitivities through the Greeks.

We will be forecasting Amazon's volatility (ticker: AMZN). We're bullish on AMZN since its price has increased by 10%, and growth at Amazon Web Services, or AWS, is accelerating due to generative AI integration. Sales have jumped, and profits in Q1 are impressive. Despite the layoffs and restructuring of the company, AMZN has shown remarkable returns, and its shares are still "undervalued" due to a mismatch between its valuation metric and growth expectations (EBITDA).

yfinance and yahoo_fin are two libraries we will use to get stock prices and option prices.

# Quantitative-Risk-Management


The project involves the creation of a system using R that not only simplifies the complex process of risk calculation but also brings reliability and precision to risk assessment. By leveraging advanced computational methods such as Monte Carlo simulations, historical data analysis, and parametric approaches, the system is designed to compute critical risk measures, including Value at Risk (VaR) and Expected Shortfall (ES). Furthermore, the system's flexibility allows for the incorporation of various stocks and options, accommodating diverse investment strategies and market conditions.

Methodology
1. Windowed Estimation GBM: A variant of the parametric approach, it assumes asset prices follow a Geometric Brownian Motion. Parameters (drift and volatility) are estimated using a rolling window of historical data.

2. Parametric Approach: Assumes that portfolio returns are normally distributed. It requires estimates of the mean and standard deviation of portfolio returns.

3. Historical Data approach: This approach uses actual historical returns to estimate potential future losses.

4. Monte Carlo Simulation: Monte Carlo simulation involves generating a large number of potential future
price paths for the assets in a portfolio based on their historical volatility and drift (mean
return).

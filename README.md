# Portfolio-Optimization
We create a program that computes the ideal portfolio weights that must be assigned to the stocks you wish to have in your portfolio, given the expected returns through historical analysis.



Steps Followed

1. Enter the stock numbers you wish to have in your portfolio.
2. Enter the Ticker Symbols of these stocks.
3. Based on this we get Yahoo finance data from your entered start date to today.
4. Daily returns are averaged and annualized, this gived us to work with the expected returns.
5. Similarly we calculate the volatility and use efficient frontier concept to return the max sharp raio.


1st we simulate weights based on Random number generator and return the higest sharpe ratio.
2nd we use SLSQP to optimize the weights by minimizing the negative sharpe ratio.

the weight results of both are plotted.

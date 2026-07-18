# Stock-Portfolio-Optimisation-Project
Notebook containing my personal contributions to the Stocks group project

The task was to find the number of stocks and weights that results in an optimal portfolio for a particular time period. The aim was to find a set of stocks and weights that would give higher returns at a lower risk using 3 different weight strategies: Absolute Weights (Buy full shares), Relative Weights (percentage allocation to each stock) and Dynamic weights (weights update at periodic intervals with respect to market conditions). 

My personal contribution involved:
- Defining a function to calculate Sharpe ratio, which informed us of the best stocks to focus on
- Attempting optimisation algorithms which were useful when implementing each weight strategy
- Developing a full dynamic weighting strategy that allows customers to choose their level of risk at each interval
- Generating efficiency frontiers which show the return vs risk graph at each interval and highlighting the point with the maximum Sharpe ratio
- If the point with maximum Sharpe ratio was chosen at each interval, the expected returns would be 37%

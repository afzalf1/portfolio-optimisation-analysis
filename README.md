```
This project explores portfolio optimisation techniques using Python. It includes analysis of risk vs. return tradeoffs, Lagrange multipliers and Monte Carlo simulations for portfolio optimisation, and visualization of the efficient frontier.

## Features

- Uses two different methods to optimise a portfolio.
- Simulates thousands of portfolios with different asset weight combinations.
- Calculates expected return, volatility, and Sharpe ratio.
- Visualizes efficient frontier and highlights optimal portfolio.
- Built entirely using `pandas`, `numpy`, `matplotlib`, and `seaborn`.

## Technologies Used

- Python 3
- Jupyter Notebook
- NumPy
- pandas
- matplotlib

## Comparing the two optimisation methods

- Lagrange multipliers provided a more accurate portfolio when finding the portfolio to minimise risk
- Lagrange multipliers were much less computationally expensive as Monte Carlo required creating thousands of simulations to improve accuracy

- Monte Carlo had the benefit of choosing to not short-sell, meaning you can choose the optimal portfolio with no negative weights
```

# Module_4_Challenge
This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that's both inexpensive and high quality. The firm uses algorithms to build each client's portfoliol. The algorithms choose from various investment styles and options. 

---
## Technologies
This platform leverages python 3.8.8 in jupyter lab 3.0.14 with the following packages:
- [Anaconda](https://www.anaconda.com/products/individual) - Pandas is included in Anaconda distribution and Conda package manager to manage Python environments.
- [Jupyter Lab](https://jupyter.org/) - web-based user interface designed for data analysis. It lets you write, run, and review the results in Python programs (all in a single integrated development environment (IDE).
---
## Installation Guide
- [pandas](https://pandas.pydata.org/) - open source data analysis and manipulation tool, built on top of python programming language.
- [numpy](https://numpy.org/) - allows for mathematical operations in python.
- [Path](https://docs.python.org/3/library/pathlib.html) - is a function from pathlib module 
- [matplotlib](https://matplotlib.org/) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

---
## Usage
```
# Calculate and plot the cumulative returns of the 4 fund portfolios and the S&P 500
# Review the last 5 rows of the cumulative returns DataFrame
whale_navs_cumulative_returns = (1+ whale_navs_daily_returns).cumprod()
whale_navs_cumulative_returns.tail()

# Visualize the cumulative returns using the Pandas plot function
# Include a title parameter and adjust the figure size
whale_navs_cumulative_returns.plot(legend=True, figsize=(15,15), title="Cumulative Returns For Whales ")

```


---
## Contributors
Presented by Bina Jariwala 

---
## License
none

---

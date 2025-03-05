# README

## Project Overview

Project 02 calculates Value at Risk (VaR) and Expected Shortfall (ES) for a portfolio consisting of stocks and options. The code includes tasks such as calculating implied volatility, the Greeks of options (Delta, Vega, Theta), and testing Put-Call Parity. Additionally, I implement Monte Carlo Simulation and Delta-Normal Approximation to estimate portfolio risks. I also calculate arithmetic returns, log returns, and evaluate the portfolio's current value.

## Requirements

To run this project, ensure you have the following packages installed:

```python
import pandas as pd
import numpy as np
import scipy.stats as stats
import matplotlib.pyplot as plt
from scipy.stats import t, norm
from scipy.optimize import root_scalar
import matplotlib.pyplot as plt
```

## Installation

To install the required dependencies, run:

```bash
pip install pandas numpy scipy matplotlib
```

## Running the Code

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook file (`project02.ipynb`) and execute the cells in order.

## Output

- The program will generate statistical summaries and visualizations.
- Code results will be displayed in the notebook file (`project02.ipynb`).
- A document (PDF) with  responses will be generated: `project02_answer.pdf`


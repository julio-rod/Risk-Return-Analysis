# Risk-Return-Analysis
This Jupyter notebook demonstrates data preparation, analysis, and visualizations for key risk and return metrics.
# Dataset
The dataset used in this analysis is:
* whale_navs.csv: Located in the "Resources" folder.
# Analysis Steps
The analysis was conducted in several steps:
1. Data Collection: Collecting CSV data into a jupyter notebook file. 
2. Analyzing: Calculating the risk of the assets in the DataFrame in comparison to the S&P 500. This analysis covers important measurements of risk and return, such as daily returns, standard deviation, Sharpe ratio, and beta. This demonstrates the risk-return characteristics of the assets and how they perform in relation to the market benchmark.
3. Evaluation: An examination of each asset, utilizing rolling statistics to monitor the risk-return dynamics.

# Libraries and Dependencies


`from pathlib import Path`

`import pandas as pd`

`import numpy as np`

`%matplotlib inline`

# Sources

[Bootcamp Spot](https://courses.bootcampspot.com/courses/2916/pages/4-dot-3-6-activity-rolling-windows?module_item_id=871726)

[Google](https://www.google.com/)
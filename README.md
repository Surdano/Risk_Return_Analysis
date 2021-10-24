# Risk-Return-Analysis

![Photo of a risk dial being turned to move the needle to Max return.](https://cdn.corporatefinanceinstitute.com/assets/risk-and-return.jpg)

---
This program utilizes Jupyter Lab to visualize performance history metrics from four large hedge funds and the S&P 500. The metrics being visualized in this program are: Daily Performance, Risk, Volitlity, Sharpe Ratio and Beta Measurements. 

At the end of the analysis we take the two funds with the highest risk-to-return profiles and compare them against each other and the S&P 500. Once determined, a recommendation is made for which fund is the better investment.

---
## Technologies

This program runs on [Python 3.7](https://www.python.org/) and utilizes:
* [Jupyter Lab](https://jupyter.org/install)
* [Pandas](https://pandas.pydata.org/)

---
## Installation Guide

The dependencies needed to run the Risk-Return-Analysis:

```python
import pandas as pd
from pathlib import Path
import numpy as np
%matplotlib inline
```

---
## Usage

Launch Jupyter Lab with the Jupyter Notebook file:
```python
risk_return_analysis.ipynb
```

Once the program is launched and the dependencies are run, the user will start seeing the calculated metrics being ploted as such:

### Daily Returns:
![Screen shot of daily returns](https://user-images.githubusercontent.com/89755088/138616603-3c5e0581-b90d-4a0c-a3ac-2f4b4ca27fd1.png)

### Cumulative Returns:
![Screen shot of cumulative returns](https://user-images.githubusercontent.com/89755088/138614953-ef9c5600-77fe-45b9-99b9-f67f97efbadb.png)

---
## Analysis
The complete analysis of the program shows that Berkshire Hathaway has the highest risk-return profile of all four funds. It also shows the highest cumulative return of the four while providing less risk than the S&P 500.

---
## Contributors
The starter code was created by © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand.

All additional code added for use and functionality was done by Thomas Leahy, thomasleahy6@gmail.com

---
## Licence
MIT Licence

2021 Thomas Leahy


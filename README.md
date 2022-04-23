# Module-Challenge-5


---

## Technologies


The Application has specific technologies that will be needed to run properly.


**Languages Required:** *Python*

**Libraries Required:** *Pandas, MatplotLib, Dotenv, alpaca_trade_api, MCForecasttools, Os, Requests, & Json*

Before running the application the following Libraries will need to be imported:

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```


Further details denoting requirements and verions are available in the requirements file.            

[Requirements](./requirements.txt)


---

## Installation Guide

This app will not work without the proper technologies listed above.  To ensure you have the applicable tools please install the requirements for the Risk Return Analysis Application using the text file in the Module-Challenge-4 folder as follows:

In The Terminal Run:

```python

pip install -r requirements.txt

```


---

## Usage



### **For Coding Purposes:** 


1. The application intially uses JSON and Requests to get Cryptocurrency information from API's using two URL's.
2. The second set of data uses Alpaca API and getenv to get stock and bond details.
3. Prepare and analyze the data using analysis, statistics, charts, and simulations. 


### **For Users:** Use the Financial Planning Application to gain  insight around portfolio expecations:

The application includes the following analyses, charts, and simulations

**Analyses, Charts, and Simulations**
 
1. Stock, Bonds, and Cryptocurrency Values
2. Portfolio Values
3. Monte Carlo Simulation (10 Year and 30 Year)
4. Monte Carlo Simulation Plot Distribution (10 Year and 30 Year)
5. Monte Carlo Simulation Summary Statistics




**A display of the Monte Carlo Simulation Chart is listed below**

![MC](https://github.com/TracyMichael/Module-Challenge-5/raw/main/images/Monte_Carlo_Simulation.png)


---

## Contributors

Tracy Davis <TracyMDavis88@gmail.com>

[Tracy Davis LinkedIn](https://www.linkedin.com/in/tracy-davis-mba-ma-2940a232/)

---

## License

MIT License

Copyright (c) [2022] [Tracy Davis]




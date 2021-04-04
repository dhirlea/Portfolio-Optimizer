# Portfolio-Optimizer

Please note this is not production ready code and subject to constant development and change. This is project is a part time endeavour which I look to work on at the weekend :) 

Portfolio optimization project using a web scraper on yahoo finance. 
User provides a dictionary of security names and yahoo symbols in the first jupyter notebook cell. They can specify the lookback period for the analysis as well as an annualisation factor. By default all computations are performed to yesterday's close of business.
The notebook computes the weights allocated to each security in order to form a mean-variance efficient portfolio. There is also backtesting functionality which provides comparative information of the portfolio performance vs an equally weighted benchmark given a pre-specified rebalancing strategy.

# Visualize-pareto-front-of-your-portfolio
A very simple method but easily customizable code snippet to visualize the pareto front for different distributions of selected stocks. In effect, it could be used to check which modifications one could make to ones own portfolio in order for it to fit ones preferences in terms of expected return and risk. Taking on too much risk without gaining expected return is after all never a good deal.

It has the following dependencies: numpy as np, pandas as pd, yahoofinancials import YahooFinancials, datetime, random, plotly.express as px

You should be able to input your portfolio through its tickers in the variables section. If you have a huge set of stocks in it, you are maybe required to increase the number of solutions generated (both population and N) to obtain a good pareto front. Note in that case the visualization isnt useful, but you can still evaluate the results through the computed pareto front. 

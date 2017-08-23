# Time Series Timeseries Stationarity Analysis in Python

When a given data point depends on that same point's previous values, we say it is time dependent. For example, the closing price of Tesla's stock tomorrow is likely somewhere close to its closing price today. (At the very least, tomorrow's closing price is likely closer to a price this month than five months ago.)

Given the frequency of time-dependent data, time series forecasting (the applied statistical modeling of predicting future time-dependent values) is a key technique any data analyst and data scientist should possess. Foundational forecasting techniques, like autoregressive and moving average models, rely on one fundamental assumption: stationarity.

In this walkthrough, real world Portland bus ridership data is utilize to introduce how to examine time-dependent data and cause a process to become stationary. We'll discuss what it the basics of time series, means for a process to be stationary, how to apply statistical tests to determine that stationarity, clean data, and make a few plots along the way.

Very basic Python experience is expected; no need for previous time series exposure.

This repo contains a tutorial on the basics of time series analysis in Python, utilizing statsmodels to identify stationarity. 

Prepared for [JupyterCon 2017](https://conferences.oreilly.com/jupyter/jup-ny).

Subscribe to [Entropy](https://www.josephofiowa.com/entropy/) (free) to learn all things data science.
# Lecture 23: Forecasting from Time Series Data I

## Motivation

Your task is to predict the number of daily tickets sold for next year in a swimming pool in a large city. The swimming pool sells tickets through its sales terminal that records all transactions. You aggregate that data to daily frequency. How should you use the information on daily sales to produce your forecast? In particular, how should you model trends, and how should you model seasonality by months of the year and days of the week to produce the best prediction?


## This lecture

This lecture discusses forecasting: prediction from time series data for one or more time periods in the future. The focus of this chapter is forecasting future values of one variable, by making use of past values of the same variable, and possibly other variables, too. We build on what we learned about time series regressions in [lecture16-timeseries-regression](https://github.com/gabors-data-analysis/da-coding-python/tree/main/lecture16-timeseries-regression). We start with forecasts with a long horizon, which means many time periods into the future. Such forecasts use the information on trends, seasonality, and other long-term features of the time series. 

Case study:
 - [Chapter 18, A: Forecasting daily ticket sales for a swimming pool](https://gabors-data-analysis.com/casestudies/#ch18a-forecasting-daily-ticket-sales-for-a-swimming-pool)

## Learning outcomes
After successfully completing [`long_term_swimming.ipynb`](https://github.com/gabors-data-analysis/da-coding-python/blob/main/lecture23-long-term-time-series/long_term_swimming.ipynb), students should be able:

  - Data munging with time series (review)
  - Adding deterministic variables such as trends, yearly/mounthly/weekly seasonality
  - Adding deterministic variables with `pandas_market_calendars` package such as holidays, weekdays, etc.
  - Sample splitting with time series
  - Simple linear models:
    - deterministic trend/seasonality and/or other deterministic variables (holidays, etc.)
  - Cross-validation with time series
  - `prophet` package
  - Forecasting
    - Comparing model based on forecasting performance (RMSE)
    - Graphical representation of model fit and forecasts

## Dataset used

 - [swim-transactions](https://gabors-data-analysis.com/datasets/#swim-transactions)

## Lecture Time

Ideal overall time: **50-60 mins**.


## Further material

  - This lecture is a modified version of [ch18-swimmingpool-predict.ipynb](https://github.com/gabors-data-analysis/da_case_studies/blob/master/ch18-swimmingpool/ch18-swimmingpool-predict.ipynb) from [Gabor's case study repository](https://github.com/gabors-data-analysis/da_case_studies).


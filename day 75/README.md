# Combine Google Trends with other Time Series Data


What can the popularity of search terms tell us about the world? Google Trends gives us access to the popularity of Google Search terms. Let's investigate:

How search volume for "Bitcoin" relates to the price of Bitcoin

How search volume for a hot stock like Telsa relates to that stock's price and

How searches for "Unemployment Benefits" vary with the actual unemployment rate in the United States



# What you'll learn today

How to make time-series data comparable by resampling and converting to the same periodicity (e.g., from daily data to monthly data).

Fine-tuning the styling of Matplotlib charts by using limits, labels, linestyles, markers, colours, and the chart's resolution.

Using grids to help visually identify seasonality in a time series.

Finding the number of missing and NaN values and how to locate NaN values in a DataFrame.

How to work with Locators to better style the time axis on a chart

Review the concepts learned in the previous three days and apply them to new datasets


# Learning Points & Summary
In this lesson we looked at how to:

How to use .describe() to quickly see some descriptive statistics at a glance.

How to use .resample() to make a time-series data comparable to another by changing the periodicity.

How to work with matplotlib.dates Locators to better style a timeline (e.g., an axis on a chart).

How to find the number of NaN values with .isna().values.sum()

How to change the resolution of a chart using the figure's dpi

How to create dashed '--' and dotted '-.' lines using linestyles

How to use different kinds of markers (e.g., 'o' or '^') on charts.

Fine-tuning the styling of Matplotlib charts by using limits, labels, linewidth and colours (both in the form of named colours and HEX codes).

Using .grid() to help visually identify seasonality in a time series.

# Module-11-Challenge
Module 11 Challenge of FinTech Bootcamp

for this challenge, I coded a Jupyter notebook that prepared, analyzed and visualized time series data using Google search traffic, stock prices and daily revenue data.

## High-Level Steps
Step 1: Find unusual patterns in hourly Google Search traffic.

Step 2: Mine the search traffic data for seasonality.

Step 3: Relate the search traffic to stock price patterns.

Step 4: Create a time series model by using Prophet.

Step 5 (optional): Forecast the revenue by using time series models.

## Files
The Starter_Code folder contains the data files provided to complete this challenge.

The forecasting_net_prophet Jupyter notebook contains the code for data preparation, data analysis, Prophet models and data visualizations.

## Findings
By isolating the search trend data for the month of May 2020 I found there was an increase in search traffic that month compared to the medain monthly search traffic.
[![Search Trends for May 2020](Search Trends for May 2020.png)](https://github.com/JulHendrickson/Module-11-Challenge/blob/main/Images/Search%20Trends%20for%20May%202020.png)

Visualizing the hour of the day and day of week search traffic as a heatmap showed search trends are higher in the middle of the week, days 2, 3 and 4. Always during the first two and last two index hours.
![Search Trends on a Heatmap](Heatmap.png)

Grouping the hourly search data allowed me to plot the average traffic by the week of the year and showed the search traffic seemed to increase during the winter holiday period, specifically between weeks 41 and 50.
![Average Traffic by the Week of the Year](Average Traffic by Week of Year.png)

Using the stock price csv I plotted the closing price and saw a drastic increase towards the end of 2020.
![Stock Price](Stock Price.png)

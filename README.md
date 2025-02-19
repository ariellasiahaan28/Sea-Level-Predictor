# Sea-Level-Predictor

Note: This project was created in 2023 on Replit and has been moved to GitHub in 2025 for convenience

The Sea Level Predictor project involves using a dataset to model and predict sea-level rise over time. The task requires creating a linear regression model to forecast future sea levels based on historical data, using Python and libraries like Matplotlib and pandas for data manipulation and visualization. This project provides hands-on experience in working with time-series data and regression analysis.

I analyze a dataset of the global average sea level change since 1880, using the data to predict the sea level change through year 2050.

Use the data to complete the following tasks:

- Use Pandas to import the data from epa-sea-level.csv.
- Use matplotlib to create a scatter plot using the Year column as the x-axis and the CSIRO Adjusted Sea Level column as the y-axis.
- Use the linregress function from scipy.stats to get the slope and y-intercept of the line of best fit. Plot the line of best fit over the top of the scatter plot. Make the line go through the year 2050 to predict the sea level rise in 2050.
- Plot a new line of best fit just using the data from year 2000 through the most recent year in the dataset. Make the line also go through the year 2050 to predict the sea level rise in 2050 if the rate of rise continues as it has since the year 2000.
- The x label should be Year, the y label should be Sea Level (inches), and the title should be Rise in Sea Level.
- The boilerplate also includes commands to save and return the image.

# Development
For development, code is written in sea_level_predictor.py and main.py to test your code.

# Testing
The unit tests for this project are in test_module.py. I imported the tests from test_module.py to main.py for convenience.

# Data Source
Global Average Absolute Sea Level Change, 1880-2014 from the US Environmental Protection Agency using data from CSIRO, 2015; NOAA, 2015.



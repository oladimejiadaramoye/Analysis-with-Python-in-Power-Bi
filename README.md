**I imported financial data from Yahoo Finance directly in Power BI, using Python to visualize the data using line charts, area charts, scatter plots, box plots, violin plots and histogram in Python within Power BI.**

The advantage over using MS Excel is that the whole process was automated, from data retrieval, processing, visualization and in real-time.

Walk through:

**1. Installation of Libraries:**

Install the following libraries;
i. yfinance: Used to download financial data from Yahoo Finance.
ii. matplotlib: A plotting library for creating static, animated, and interactive visualizations in Python.
iii. pandas: A data manipulation and analysis library.


**2. Data Retrieval:**

I used yfinance to download Tesla's stock data from January 1, 2021, to January 1, 2024.
The data is then reset to have the date as a separate column, which is important for time-series analysis.

**3. Data Visualization:**

Several types of visualizations were created using matplotlib and seaborn:
i. Line and area charts to show the trend of Tesla's closing stock price over time.
ii. Box and violin plots to display the distribution of the closing price and trading volume.
iii. A violin plot with splits by quarter to compare the distribution of trading volumes across different quarters of each year.
iv. A histogram with a kernel density estimate (KDE) to show the distribution of trading volumes across different years.
v. A scatter plot that uses color coding to differentiate between days when the stock price closed up versus when it closed down, with transparency to manage overlapping points.

**4. Scatterplot Details:**

The scatter plot compares the trading volume with the closing price over the years. 
It uses color coding (green for up, red for down) based on whether the closing price was higher or lower than the previous period,
providing a quick visual reference for price movement direction relative to volume.

**in conclusion**, With these plots, I was able to show how python can be used to easily visualise and analyze Tesla's stock performance over the specified period, which is a faster and more effective method. 

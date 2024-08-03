# META-FINACIAL-ANALYSIS-
![](https://github.com/lexcytech/META-FINACIAL-ANALYSIS-/blob/main/meta_PNG5.png)
## Overview
The data used for analysis in this project was sourced from Yahoo Finance, a well-known and reliable provider of financial news, data, and commentary. Yahoo Finance is a popular resource for obtaining historical and real-time data on stocks, indices, commodities, currencies, and other financial instruments. The specific dataset in this project pertains to historical stock price data.
---
## Data Source
•	Website: Yahoo Finance.

•	Access Date: [July 21, 2024].

•	Data Download URL: [https://finance.yahoo.com/quote/META/history/].
---
## Dataset Description
The dataset contains historical daily stock prices, including various attributes such as opening price, high price, low price, closing price, adjusted closing price, and trading volume. This data is crucial for performing time series analysis, descriptive statistics, correlation analysis, volume analysis, and risk analysis.

![](https://github.com/lexcytech/META-FINACIAL-ANALYSIS-/blob/main/RAW-DATA.png)

## Data Columns
1.	**Date**: The date of the trading day.
2.	**Open**: The opening price of the stock on the given date.
3.	**High**: The highest price of the stock during the trading day.
4.	**Low**: The lowest price of the stock during the trading day.
5.	**Close**: The closing price of the stock on the given date.
6.	**Adj Close**: The closing price of the stock adjusted for corporate actions such as stock splits, dividends, and other distributions.
7.	**Volume**: The total number of shares traded during the trading day.
   
## Data Integrity and Quality
The data from Yahoo Finance is generally considered accurate and reliable, sourced directly from stock exchanges and financial institutions. However, users should still perform necessary data cleaning and validation steps, such as checking for missing values, outliers, and inconsistencies.

## Data Usage and Licensing
The data obtained from Yahoo Finance is intended for personal use, research, and educational purposes. Users should review Yahoo Finance's terms of service and data usage policies to ensure compliance, especially if the data will be used for commercial purposes.

## Problem Statement
The objective of this analysis is to gain insights into the stock price and trading volume patterns of Meta company, as captured in the historical data sourced from Yahoo Finance.
The analysis will be conducted using Power BI, leveraging its capabilities for data visualization and DAX for measure calculations. The findings will help in understanding market dynamics, making informed investment decisions, and providing actionable insights for stakeholders interested in the stock's performance.
## DATA Cleaning Steps 
•	Date: Reformatted to display the full date in a readable format.

•	Open, High, Low, Close, Adj Close: Numeric columns ensuring consistency and appropriate formatting for further analysis.

•	Volume: Numeric column formatted for consistency.

## Transformation Steps
1.	**Date Formatting**:	In the cleaned dataset, the dates have been reformatted for better readability, including the day of the week.
2.	**Data Type Consistency**:	All numeric columns (Open, High, Low, Close, Adj Close, Volume) were ensured to have consistent numeric data types.
3.	**Calculation of Additional Metrics**:Average Closing Price for Current Month: Calculated using DAX to provide insights into the monthly performance.
  -	Average Closing Price for Previous Month: Another DAX measure to compare month-over-month performance.
  -	Average Opening Price for Current and Previous Month: Calculated to analyze the stock's opening trends.
  - Average Volume for Current and Previous Month: Provides insights into trading activity.
  - Percentage Difference in Volume: A DAX measure to understand changes in trading volume between the current and previous months.

![](https://github.com/lexcytech/META-FINACIAL-ANALYSIS-/blob/main/TRANSFORMED-DATA%20.png)
---

## Visuals and Analysis:
1.	**Date Range Selector(Slicer)**:
-	Purpose: Allows users to filter the data based on a specific date range, enabling a focus on recent trends or historical comparisons.
2.	**Average Opening Price (Current Month vs. Previous Month)**:
- Current Month: Displays the average opening price of the stock for the current month, which is $506.40.
- Previous Month: Shows the average opening price for the previous month, which is $499.13.
- Analysis: Comparing these values helps identify any changes in investor sentiment or market conditions influencing the stock's opening price.
3.	**Percentage Difference in Volume**:
-	Metric: Indicates the percentage difference in trading volume between the current and previous months, which is 22.82%.
-	Analysis: This metric highlights changes in trading activity, suggesting shifts in market interest or significant events affecting the stock. 
4.	**Volume by Year**:
-	Graph: A line chart illustrating the monthly trading volumes for the current year.
-	Purpose: Provides a visual representation of trading activity, showing peaks and troughs that could correlate with market events or news.
5.	**Average Closing Price (Current Month)**:
-	Metric: Displays the average closing price for the current month, recorded at $505.02.
-	Analysis: Offers a quick snapshot of the stock's performance, helping to assess overall market trends and investor sentiment
6.	**Trend of Average Opening and Closing Price**:
-	Visualization: A combined line and area chart showing the trends of average opening and closing prices over the months.
- Purpose: Helps in visualizing the relationship and movement between opening and closing prices, aiding in understanding market volatility and investor behavior.
7. **Trend of Average Closing Price**:
-	This line chart illustrates the trend of the stock's average closing price over time, showing a consistent upward trajectory. This indicates a general increase in the stock's value, which could be due to positive market sentiment, company performance, or other external factors.
8. **Trend of Weekly Opening Price**:
•	The chart displays the weekly average opening prices, demonstrating an upward trend with occasional fluctuations. This suggests a general increase in the stock's initial trading value each week, providing insights into how the stock opens relative to the previous weeks.
9. **Average Volume Current vs. Previous Month**:
•	The dashboard compares the average trading volumes of the current month (14.67M) with the previous month (11.94M), highlighting an increase. A rise in trading volume can indicate higher investor interest or increased market activity, possibly in response to news, events, or market conditions.
10. **Average Closing Price Previous Month**:
- The value of 500.65 represents the average closing price of the stock in the previous month. This metric provides a benchmark for assessing the current month's performance and helps in understanding recent price movements.
  
![](https://github.com/lexcytech/META-FINACIAL-ANALYSIS-/blob/main/DASHBOARD1.png)
![](https://github.com/lexcytech/META-FINACIAL-ANALYSIS-/blob/main/DASBOARD%202.png)

## Key Findings
1.	Average Prices: The average opening and closing prices have shown a general upward trend over the analyzed period, indicating a potential appreciation in the stock's value.
2.	Trading Volume: The analysis revealed fluctuations in trading volumes, with notable increases in specific months, which could indicate periods of heightened investor interest or market activity.
3.	Percentage Change: A significant percentage difference in trading volume was observed, suggesting changes in investor behavior or external market influences.
4.	Comparison: The comparison of average prices and volumes between the current and previous months provided insights into short-term trends and market sentiment.

## Overall Recommendation:
Based on the analysis of the stock's performance as depicted in the dashboards:
1.	Positive Market Sentiment:
-	The upward trends in both average opening and closing prices suggest a positive market sentiment towards the stock. This trend may indicate continued growth potential, making it an attractive option for investors looking for stocks with an upward trajectory.
2.	Increased Trading Volume:
-	The observed increase in trading volume from the previous month indicates heightened investor interest. This could be a sign of growing confidence in the stock, potentially driven by favorable company news, strong financial performance, or broader market trends.
3.	Investment Opportunities:
-	Given the consistent increase in stock prices and trading volume, investors may consider buying or holding the stock, especially if these trends are supported by fundamental analysis and other market conditions. However, it is advisable to monitor for any signs of market correction or external factors that could impact the stock's performance.
4.	Risk Management:
o	While the upward trends are promising, investors should also consider implementing risk management strategies. This includes setting stop-loss orders to protect against sudden market downturns and diversifying their investment sportfolio to mitigate potential risks.

## Summary 
1.	Investment Consideration: Given the upward trend in average prices, investors may consider this stock for potential investment, keeping in mind market conditions and individual risk tolerance.
2.	Market Monitoring: The fluctuations in trading volumes suggest that continuous monitoring is essential to understand the factors driving market activity.
3.	Further Analysis: Additional analysis, including fundamental and technical analysis, could provide a deeper understanding of the stock's future performance potential.
This comprehensive analysis provides valuable insights into the stock's performance and market behavior, aiding in informed investment decisions.**







   

# prophet-challenge
# Data Source: Module 8 activities and Xpert Learning Assistant
# The monthly median across all months is 35,172 searches and the total search traffic in May 2020 was 
# 38,181
# After Grouping the hourly search by hour of the day, day of the week, and week of the year, the following observations can be made:
    # The search traffic is not relatively consistent by search by hour of the day. It peaks at around
    85 million views at 11pm to 12am and has less than 20 million searches between 5am and 11am.
    # However the average search traffic is relatively consistent by day of the week between 40 million and 50 million searches every day of the week.
    # The average search is s wave like pattern every 20 weeks or so from 40 million to 50 million searches. But the highest (strongest) wave is noticeable in the first 8 weeks of the year. In weeks 40 to 51 it starts rising as the holiday season and peaks before new year before falling in the last week prior to new year celebration.
# Market events emerged during the year of 2020 that many companies found difficult. But, after the initial shock to global financial markets, new customers and revenue increased for e-commerce platforms. Slice the data to just the first half of 2020 (2020-01 to 2020-06 in the DataFrame), and then plot the data. Do both time series indicate a common trend that’s consistent with this narrative? 
    # Yes. There is a down trend in both time series that is consistent with the narrative of an initial shock followed by an uptrend with a sharp upward spike in both time series that ocurred in early May 2020.
# Review the time series correlation, and then answer the following question: Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
    # No. The values are very close to zero and therefore don't suggest a strong predictable relationship, for e.g. The correlation co-efficient between stock volatility and Lagged Search Trends of -0.254764 is close to zero and is of no importance. 
# Near term forecast
    # shows a declining trend with time. See declining yhat in decling range of upper and lwoer bounds with passage of time from June to November. 
# What time of day exhibits the greatest popularity?

**Answer:12am
# Which day of week gets the most search traffic?

**Answer:Tuesday

# What's the lowest point for search traffic in the calendar year?

**Answer:October
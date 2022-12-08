# ZING42_PYTHON_INTERNSHIP_ASSIGNMENT


Acquire Data:

1. Programatically fetch “Securities available for Equity segment (.csv)” file From the URL: https://www.nseindia.com/market-data/securities-available-for-trading
2. Programatically get the latest “bhavcopy” csv file from the following URL - https://www.nseindia.com/all-reports
3. Construct a (relational) database with normalized tables & insert both the data files into it
4. In addition to step 2, programmatically get bhavcopies of the last 30 days instead of just the latest one.

Queries:

1. Write a SQL query to fetch the top 25 gainers of the day sorted in the order of their gains. Gains is defined as [(close - open) / open] for the day concerned as per point 2 above. 
OUTPUT IS:

![image](https://user-images.githubusercontent.com/63302398/206191038-057c00c7-a66e-4ec4-bb9f-27bed4ccb850.png)



2. Get datewise top 25 gainers for last 30 days as per point 4 above.
OUTPUT IS:

![image](https://user-images.githubusercontent.com/63302398/206191491-28d3b60a-ef27-4ba9-a13d-c7f61b8c76be.png)

Similarly whole all 30 days top 25 gainers are been listed.

3. you can also get a single list of top 25 gainers based on open of oldest day and close of latest day of those 30 days as per point 4.
OUTPUT is:

![image](https://user-images.githubusercontent.com/63302398/206380058-52477bd7-c437-4562-8b0c-937fd32a4f75.png)


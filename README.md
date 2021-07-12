# stock-analysis

## Overview
The initial task was to provide a summary of the performance of 12 stocks. Using a VBA script, we were able to compile all the data for a given year and provide a simple table that showed the stock ticker symbol, the total volume and percent return for the year. Recognizing that we may want to later expand the dataset, we then refactored the code to try to optimize it's performance.

## Results
The refactored code was able to speed up the calculation process. For both years, the run time was cut nearly in half. Please see the following timer run time message boxes for comparison:
  [2017 Original code Timer](Resources/Green_stocks_2017_Timer.png)     [2017 Refactored code Timer](Resources/VBA_Challenge_2017_Timer.png)
  [2018 Original code Timer](Resources/Green_stocks_2018_Timer.png)     [2018 Refactored code Timer](Resources/VBA_Challenge_2018_Timer.png)


## Summary
Refactoring code can be a beneficial process as you become more comfortable with what you want it to accomplish. The initial code is written for a specific data set, and while it may work fine, there is usually a way to improve it. In this case, we were looking to speed up the process. While a one second difference is not an earth shattering change for the given data set, it does have greater implications if you move from 12 stocks to all 2,400 stocks on the NYSE. Another potential improvement is making the logic and processes more clear for anyone may follow behind.

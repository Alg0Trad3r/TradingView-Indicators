# TradingView-Indicators
Library of TradingView indicators that I have developed myself during my time using more retail based strategies. I have used these indicators directly in the research process when developing strategies myself and with the completion of projects for non-institutional clients.

Regarding the reference to the library by Forrest with OGV Tech, I was working with that company (OGV Tech) and helped developed the code that was put into the library. The library was done on his account which is why the library is imported in from his account.

All of the indicators give the user the ability to change the parameters relevant to the strategy

In this repository you will find these indicators:
VWAP Strategy - This indicator is a strategy that has a algorithm for entry

    Step 1: Identifies levels of support and resistance in the pre-market 
    
    Step 2: Marks the levels that are a defined distance from VWAP 
    
    Step 3: Waits for a break of those levels and VWAP once the market opens 
    
    Step 4: Waits for a test back up to the levels and VWAP 
    
    Entry Trigger: Enters a short once price has shown it will reject VWAP with a candlestick pattern.
    
    Stop Loss is placed at the most recent high
    
    The trade is exited once a cross of the EMA on the 1 minute or 3 minute (User's choice) happens against the trade or stop loss is hit.
    Strategy comes with State Debug table that can be toggles on and off for signal checking and debugging


Daily Gap Tracker - This indicator tracks metrics on the gapping of stocks during post and pre market hours
    Displays a chart in the TradingView chart that shows the user all of the metrics that inculde:
    
      Metric 1: Date
      
      Metric 2: Gap Direction (Up/Down)
      
      Metric 3: Previous day close price
      
      Metric 4: Current day open price
      
      Metric 5: The amount of "points" the market gapped (The mathematical change between previous day close and current day open)
      
      Metric 6: The percentage of price the size of the gap is
      
      Metric 7: The percentage of the ATR the size of the gap is
      
      Metric 8: The ATR


ATR-VWAP - This indicator was created with the intent of helping out in living trading to quickly display the relationship between price, the 9 and 21 EMA, and VWAP. It also has the additional function of displaying the 9 and 21 EMA
    Displays a chart in the TradingView chart that shows the user all of the metrics that include:
    
      Metric 1: The ATR
      
      Metric 2: The percent of price that the current value of the ATR is
      
      Metric 3: The percent of the ATR that the current distance between price and VWAP is
      
      Metric 4: The percent of the measured moved (Distance between the lowest high/low and VWAP) that the distance between price and VWAP when price crosses VWAP is
      
      Metric 5: The percent of the divergence (9 EMA and VWAP moving farther apart) that the convergence (9 EMA and VWAP moving closer together) is when fully crossed


Extended Hours RVOL - This indicator tracks the volume during post and pre market sessions that is used to calculate RVOL metrics
    Displays a chart in the TradingView chart that shows the user all of the metrics that include:
    
      Metric 1: Market after hours volume
      
      Metric 2: Market after hours average volume with lookback
      
      Metric 3: Market regular hours average volume with lookback
      
      Metric 4: Market after hours RVOL relative to the after hours average volume 
      
      Metric 5: Market after hours RVOL relative to the regular hours average volume
      
      Metric 6: Pre Market Volume
      
      Metric 7: Prev (Day before) Pre Market Volume
      
      Metric 8: Regular market volume (From open to current time)
      
      Metric 9: Average calculation lookback in days

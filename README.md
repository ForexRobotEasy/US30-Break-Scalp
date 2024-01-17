# US30 Break Scalp Robot

This is the code for the US30 Break Scalp trading software. It has been developed by the Forex Robot Easy Team and can be found on their website forexroboteasy.com. Please note that ForexRobotEasy is not the official developer of this product. They are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Terms of Reference

1. Implement US30 Break Scalp trading software.
2. Follow safe trading strategies, avoid martingale.
3. Execute trades based on a specific range breakout.
4. Limit trading activity to three trades per day.
5. Optimize compatibility with IcMarkets, FTMO, and MFF brokers.
6. Allow users to adjust trading hours.
7. Conduct thorough backtesting for performance evaluation.
8. Emphasize past performance does not guarantee future results.
9. Maintain low drawdown while considering potential adversities.
10. Focus solely on code requirements and necessary features.
11. Include only essential trading functions in technical spec.
12. Size of terms of reference should not exceed 1500-2000 chars.

## Code Explanation

The code is written in MQL5 and consists of several functions and constants. Here is a breakdown of the code:

1. Constants:
   - `MAX_TRADES_PER_DAY`: This constant defines the maximum number of trades allowed per day.

2. Expert initialization function (`OnInit`):
   - This function is called when the expert advisor is initialized.
   - Initialization code can be added here.

3. Expert deinitialization function (`OnDeinit`):
   - This function is called when the expert advisor is deinitialized.
   - Deinitialization code can be added here.

4. Expert tick function (`OnTick`):
   - This function is called on each tick of the market.
   - Tick processing code can be added here.
   - It checks if the maximum number of trades per day has been reached and returns if true.
   - It checks if the current hour is within the specified trading hours and executes the range breakout strategy if true.

5. Range breakout strategy function (`RangeBreakoutStrategy`):
   - This function executes the range breakout strategy.
   - Range breakout strategy code can be added here.

6. Total trades function (`TotalTrades`):
   - This function counts the number of trades executed.
   - Code to count the total number of trades executed can be added here.

## Product Description

The US30 Break Scalp Robot is a trading software developed by the Forex Robot Easy Team. It follows safe trading strategies and avoids martingale. The software executes trades based on a specific range breakout strategy. It limits trading activity to three trades per day to maintain control over risk exposure.

The US30 Break Scalp Robot has been optimized for compatibility with IcMarkets, FTMO, and MFF brokers. It allows users to adjust the trading hours according to their preferences. Thorough backtesting is recommended to evaluate the performance of this software.

Please note that past performance does not guarantee future results, and maintaining low drawdown is crucial while considering potential adversities. The US30 Break Scalp Robot focuses solely on code requirements and necessary features, ensuring efficiency and reliability.

For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/us30-break-scalp-review-safe-optimized-forex-software/).

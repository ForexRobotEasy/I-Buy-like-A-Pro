# I Buy like A Pro - ReadMe

## Developer
- Developer: Forex Robot Easy Team
- Developer's site: [forexroboteasy.com](https://forexroboteasy.com)

## Program Description
This code is a sample implementation of the 'I Buy like A Pro' trading strategy. It is designed to execute buy trades in quiet night market conditions. The program calculates the lot size based on the maximum acceptable loss and stop loss defined in the code constants. It uses the Trade and PositionInfo libraries for trade execution and information retrieval.

## Required Libraries
- Trade.mqh
- PositionInfo.mqh

## Constants
- TP_PERCENT: Take profit percentage
- SL_PERCENT: Stop loss percentage
- MAX_LOSS: Maximum acceptable loss

## Functions
### isQuietNightMarket()
- Description: Checks for quiet night market conditions
- Returns: true if conditions are met, false otherwise

### calculateLotSize()
- Description: Manages risk and calculates lot size
- Returns: calculated lot size based on account balance, stop loss, and tick value

### executeTrade()
- Description: Executes the buy trade with calculated lot size, take profit, and stop loss

## Program Execution
- The program starts in the `OnStart()` function.
- It checks for quiet night market conditions using the `isQuietNightMarket()` function.
- If the conditions are met, it executes the buy trade using the `executeTrade()` function.

## Product Description
I Buy like A Pro is a forex trading strategy designed to take advantage of quiet night market conditions. It uses a combination of risk management techniques and technical analysis to execute buy trades with calculated lot sizes, take profit, and stop loss levels.

This code is a sample implementation of the I Buy like A Pro strategy. It has been developed by the Forex Robot Easy Team and is provided as an example of how the strategy can be implemented. Please note that ForexRobotEasy is not the official developer of this product. For detailed reviews and trading results of the official product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/i-buy-like-a-pro-review-and-download-forex-software-for-real-results/).

To find the official developer of the I Buy like A Pro strategy and to obtain the official version of the product, please refer to MQL5.

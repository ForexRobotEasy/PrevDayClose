# PrevDayClose

This program is designed to analyze the Forex market using the closing price of the previous day to predict market trends. It draws a horizontal line at the closing price, which serves as a benchmark for market direction.

## Indicators

The program utilizes the following indicators:

- Chart window
- Indicator buffer (1 buffer)
- Blue color for the indicator line

## Input parameters

- Timeframe: The timeframe to be used for analysis. The default timeframe is Daily (PERIOD_D1).

## Global variables

- prevDayCloseBuffer: A buffer to store the previous day's closing price.

## Custom indicator

The program defines a custom indicator named PrevDayClose. The indicator initializes the indicator buffer and sets the indicator label based on the selected timeframe.

## Custom functions

### DrawPrevDayClose()

This function calculates the previous day's close price and draws a horizontal line at that price. The line is created using the ObjectCreate() function and customized using the ObjectSet() function.

## Indicator start

The OnCalculate() function is the entry point for the indicator. It is called every time a new bar is formed. In this function, the previous day's close price is calculated and stored in the buffer. The DrawPrevDayClose() function is called to draw the horizontal line.

## Product Description

PrevDayClose is a Forex market analysis tool developed by Forex Robot Easy Team. It utilizes the closing price of the previous day to predict market trends and draw a benchmark line for market direction.

The software is designed to be flexible and user-friendly, allowing users to select timeframes and draw lines to the close prices of the previous day. It provides users with a clear picture of the market's direction at any given moment, which is crucial for profitable currency trading.

The code includes necessary trading functions to implement the PrevDayClose algorithm. It can be used as a standalone tool or integrated into existing trading systems.

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/prevdayclose-forex-software-reviewing-market-direction-tool/).

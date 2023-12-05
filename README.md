# Breakout Project

This is the code for the Breakout Project Forex robot, developed by Forex Robot Easy Team. 

For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/breakout-project-forex-software-review-real-results-and-download-options/).

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Description

The Breakout Project Forex robot is designed to trade breakouts in the financial markets. It provides two trading modes: Pending Order and Market Order.

### Input Parameters

- `Mode`: Select the trading mode. Available options are `MODE_PENDING_ORDER` and `MODE_MARKET_ORDER`.
- `StopLoss`: Stop loss in points.
- `TakeProfit`: Take profit in points.
- `TrailingStop`: Trailing stop in points.
- `MinimumDeposit`: Minimum deposit required to run the robot.

### Initialization

The `OnInit` function is called during the initialization of the expert advisor. It checks if the minimum deposit requirement is met. If the requirement is not met, it prints an error message and removes the expert advisor. The selected trading mode is also printed.

### Deinitialization

The `OnDeinit` function is called during the deinitialization of the expert advisor. It can be used for any necessary cleanup tasks.

### Trading

The `OnTick` function is called on every tick of the market. In this function, the pending order or market order is placed based on the selected trading mode. Stop loss and take profit levels are set, and trailing stop is applied.

Please note that the actual code for placing pending orders and market orders, setting stop loss and take profit levels, and applying trailing stop is not provided in this sample code. You can refer to the official developer or the MQL5 documentation for the specific implementation.

## Disclaimer

ForexRobotEasy is not the official developer of this product. We are showcasing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5. For detailed reviews and trading results, please visit [here](https://forexroboteasy.com/forex-robot-review/breakout-project-forex-software-review-real-results-and-download-options/).

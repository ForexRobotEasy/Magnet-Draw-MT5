# Magnet Draw MT5

This code is for the **Magnet Draw MT5** script, developed by the *Forex Robot Easy Team*. The purpose of this script is to enhance the trading experience on the MetaTrader 5 platform by providing custom drawing tools with magnet snap functionality.

## Features

- The script includes custom drawing tools such as vertical lines, horizontal lines, trend lines, horizontal rays (angle trend lines), Fibonacci retracements, and rectangles.
- The drawing tools can be customized in terms of color and thickness.
- The script enables the crosshair on the chart and snaps it to the nearest price if it is within a specified threshold.
- The script allows users to draw the custom drawing tools by pressing specific keys on the keyboard.
- The script reduces CPU usage by sleeping for a short period between iterations.

## How it works

1. The necessary libraries are included and global variables are defined.
2. Custom drawing tools are defined, including functions to draw vertical lines, horizontal lines, trend lines, horizontal rays, Fibonacci retracements, and rectangles.
3. The magnet snap functionality is implemented through the `GetNearestPrice` function, which finds the nearest price to the mouse cursor position on the chart.
4. Customization options are provided for the drawing tools, including color and thickness.
5. The main program starts with the `OnStart` function, which enables the crosshair on the chart and sets the magnet snap threshold.
6. The program enters a loop until it is manually stopped.
7. Within the loop, the position of the crosshair is obtained.
8. If the crosshair is within the magnet snap threshold, it is snapped to the nearest price.
9. Based on the user's input (key presses), the corresponding custom drawing tool is drawn using the nearest price and the crosshair position.
10. The program sleeps for a short period to reduce CPU usage.

## Product Description

*Magnet Draw MT5* is a powerful script developed by the Forex Robot Easy Team to enhance the trading experience on the MetaTrader 5 platform. With this script, traders can easily draw custom lines, trend lines, Fibonacci retracements, and rectangles on their charts.

The script provides a unique magnet snap functionality, which automatically snaps the drawing tools to the nearest price on the chart. This feature ensures accurate and precise placement of the drawing tools, saving time and effort for the trader.

With *Magnet Draw MT5*, traders can easily analyze market trends, support and resistance levels, and potential trade setups. The script allows for easy customization of the drawing tools, including color and thickness, to suit individual preferences.

This product is not developed or endorsed by Forex Robot Easy or the official developer of *Magnet Draw MT5*. The provided code serves as an example of how the script works and can be implemented. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of *Magnet Draw MT5*, please visit [here](https://forexroboteasy.com/forex-robot-review/magnet-draw-mt5-forex-software-review-enhance-tradingview-experience/).

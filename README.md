# Custom TradingView Scripts

This repository contains custom scripts for TradingView's Pine Editor. These scripts add additional functionality and indicators to enhance trading analysis on the TradingView platform.

## Included Indicators

### Trade Value Display

A simple indicator that calculates and displays the trade value (volume × close price). Using a transparency technique, the indicator shows values in the Data Window without cluttering the chart.

- File: `Trade-Value-Display.pine`
- Function: Calculates trade value for each candlestick
- Display: Visible in the Data Window only
- Implementation: Uses transparency (100% transparent color) to hide the indicator on chart while maintaining Data Window functionality

## How to Use

1. Open Pine Editor in TradingView
2. Copy the content of the desired .pine file
3. Paste into the Pine Editor
4. Click "Add to Chart" to apply the indicator
5. To view the indicator values, open the Data Window (View → Data Window or press D)

## Technical Notes

- Pine Script version: v6
- The overlay parameter is set to `true` to avoid creating an additional pane below the main chart
- Transparency techniques are used to maintain Data Window functionality without visual chart elements

## Future Development

More custom indicators and trading strategy scripts will be added to this collection.

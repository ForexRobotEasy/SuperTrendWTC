# SuperTrendWTC ReadMe File

This is the ReadMe file for the SuperTrendWTC code, developed by Forex Robot Easy Team. Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work similarly to the product described below. To find the official developer of this product, please refer to MQL5.

## Product Description

The SuperTrendWTC is a custom indicator for MetaTrader 5 (MT5) that calculates the SuperTrend indicator based on the Average True Range (ATR) and a multiplier. The SuperTrend indicator is a popular trend-following indicator used by traders to identify the direction of the current trend and potential entry and exit points.

The SuperTrendWTC indicator has the following input parameters:

- AtrPeriod: Period for calculating Average True Range (ATR)
- Multiplier: Multiplier for calculating SuperTrend
- Price: Price type to be used (e.g., close price, high price, low price, etc.)

The indicator uses two global variables, SuperTrendBuffer and AtrBuffer, to store the calculated values. The trend direction is also tracked using the trendDirection variable.

The indicator has two main functions:

1. **OnInit()**: This function is called during the initialization of the indicator. It sets up the indicator buffers, styles, labels, and draw begin for the SuperTrend line. It also initializes the trend direction variable.

2. **OnCalculate()**: This function is called for each new tick or bar of data. It calculates the Average True Range (ATR) using the input parameters and stores the values in the AtrBuffer. It then calculates the upper and lower bands of the SuperTrend using the ATR and the multiplier. Depending on the current trend direction, it updates the SuperTrendBuffer and checks for trend reversals based on the close price. Finally, it returns the total number of calculated rates.

For a detailed review of this product and trading results, please visit [this link](https://forexroboteasy.com/forex-robot-review/supertrendwtc-review-profitable-mt4-forex-software-guide/).

## Disclaimer

Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work similarly to the product described above. To find the official developer of this product, please refer to MQL5.

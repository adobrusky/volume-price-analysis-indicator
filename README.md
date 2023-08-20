# VPA Indicator

The VPA Indicator is a Pine Script indicator designed to assist traders in identifying valuable Volume Price Analysis (VPA) data on price charts. This indicator aims to highlight different types of candlestick patterns and volume conditions that can provide insights into potential market direction.

## Features

The VPA Indicator includes the following features:

### Candlestick Patterns

- **Hammers and Shooters**: Identifies hammer and shooter candlestick patterns, which can indicate potential trend reversals. Hammer candles are indicated with an H and shooter candles are indicated with an S.
- **Momentum Candles**: identifies candles with significant price movement relative to Average True Range (ATR) accompanied by high volume, which may indicate potential strong market momentum. Momentum candles are indicated with an M.
- **Dojis**: Recognizes doji candlestick patterns, which may signal market indecision and/or reversal. Doji candles are indicated with a D.
- **Outside Inside Bars and Inside Inside**: Detects outside inside (OI) and inside inside (II) bars, which are patterns indicating potential continuation or reversal of trends.

### Volume Conditions

- **High Volume**: Highlights candles with unusually high trading volume compared to the average volume. A candlestick pattern that has high volume is indicated with a +.
- **Volume Anomalies**: Identifies volume anomalies, where price movements are slowing and volume is increasing, which may signal a decrease in momentum. Volume anomalies are indicated with an A.

## Configuration

The VPA Indicator offers customization options through input parameters. You can adjust the settings to match your trading preferences:

- **Show/Hide Options**: Enable or disable the display of specific candlestick patterns and volume anomalies.
- **Volume SMA Length**: Set the length of the simple moving average (SMA) used for average volume calculations.
- **Volume Thresholds**: Define acceptable and high volume thresholds as a percentage of the average volume. Indications of candlesticks and anomalies will not show on candles with below acceptable volume.
- **ATR Length and Threshold**: Configure the average true range (ATR) length and threshold for identifying momentum bars.
- **Candlestick Ratios**: Adjust various ratios used to determine the characteristics of different candlestick patterns.

## How to Use

1. Copy the provided Pine Script code.
2. Open TradingView and create or edit a chart.
3. Click on the "Pine Script" tab, paste the code into the editor, and save the script.
4. Apply the VPA Indicator to your chart by selecting it from the list of available indicators.
5. Configure the indicator's settings according to your preferences.
6. Observe the chart for highlighted candlestick patterns and volume anomalies to assist in your trading decisions.

## Disclaimer

Please note that the VPA Indicator is a tool designed to assist traders in identifying valuable price action and volume patterns. It should not be used as the sole basis for making trading decisions. Always use other technical and fundamental analysis before making any trading decisions.
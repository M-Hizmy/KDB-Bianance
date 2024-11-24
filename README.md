# KDB-Binance

## Overview
This project is a real-time KDB Ticker setup for Binance API data, designed to process and store cryptocurrency trade, quote, depth, and candlestick data in a KDB+ database. 
It includes dynamic WebSocket configurations for continuous or limited data collection.

## Features
- Real-time data ingestion from Binance API.
- Data types processed:
  - **Trade**: Records individual trades.
  - **Quote**: Tracks bid/ask prices and quantities.
  - **Depth**: Captures order book updates.
  - **Candlestick**: Provides OHLCV data for specified intervals.
- Supports continuous data collection with `run_forever` or limited messages by specifying a maximum count (change it accrodingly).

## Requirementss
- Python 3.x
- Libraries:
  - `websocket-client`
  - `pykx`
  - `logging`
  - `json`
- KDB+ ticker running on port 5010 (change it accrdingly).


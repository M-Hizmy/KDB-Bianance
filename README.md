# KDB-Binance

## Overview
TThis project is a real-time feed handler that connects to the Binance WebSocket API to collect cryptocurrency data (trades, quotes, depth, and candlesticks) and stores it in a KDB+ database. The project includes a dynamic setup for real-time data ingestion and storage in KDB+ tables.

## Features
- Real-time data ingestion from Binance API.
- Data types processed:
  - **Trade**: Records individual trades.
  - **Quote**: Tracks bid/ask prices and quantities.
  - **Depth**: Captures order book updates.
  - **Candlestick**: Provides OHLCV data for specified intervals.
- Supports continuous data collection with `run_forever` or limited messages by specifying a maximum count (change it accrodingly).


# Project Structure
FeedHandlerProject/


## Requirementss
- Python 3.x
- Libraries:
  - `websocket-client`
  - `pykx`
  - `logging`
  - `json`
- KDB+ ticker running on port 5010 (change it accrdingly).


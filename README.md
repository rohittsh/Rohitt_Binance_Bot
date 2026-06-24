## Features
- Market and Limit Order support
- Input validation and logging
- Extendable for advanced strategies (OCO, TWAP, etc.)

## Setup
1. Install dependencies:
```
pip install python-binance
```

2. Update your Binance API credentials in `src/utils.py`.

## Usage
Market Order:
``
python src/market_orders.py BTCUSDT BUY 0.01
```

Limit Order:
```
python src/limit_orders.py BTCUSDT SELL 0.01 30000
```

Logs will be written to `bot.log`.

# EURUSD 3d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_731_rows-blue)](https://getdata.finance/datasets/eurusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurusd)

### -> [**Download the full EURUSD dataset on getdata.finance**](https://getdata.finance/datasets/eurusd)

**EURUSD 3d OHLCV forex historical data** — ultra high-quality 3d OHLCV for **Euro / US Dollar**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3d OHLCV** for **Euro / US Dollar** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurusd) · **6,731** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `EURUSD_3d.csv` (76 rows, `2026-04-17` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurusd)** — **6,731** `1m` rows (~1.22 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `1971-01-02` -> `2026-07-30`.

## Download sample

**[EURUSD_3d.csv](https://github.com/getdata-finance/eurusd-3d-ohlcv-forex-historical-data/blob/main/EURUSD_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurusd-3d-ohlcv-forex-historical-data/main/EURUSD_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurusd-3d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurusd-3d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurusd-3d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurusd](https://getdata.finance/datasets/eurusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurusd))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 76 | **6,731** |
| Size | 0.01 MB | ~1.22 MB |
| Period | `2026-04-17` -> `2026-07-31` | `1971-01-02` -> `2026-07-30` |
| File | `EURUSD_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Coverage report | — | [EURUSD coverage](https://getdata.finance/coverage/eurusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/eurusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-04-17T00:00:00+00:00 | 1.23214 | 1.23894 | 1.22995 | 1.23027 | 227867 |
| 2026-04-20T00:00:00+00:00 | 1.23027 | 1.23572 | 1.22947 | 1.23551 | 183303 |
| 2026-04-21T00:00:00+00:00 | 1.23551 | 1.2358 | 1.22857 | 1.23094 | 211409 |
| 2026-04-22T00:00:00+00:00 | 1.23094 | 1.23294 | 1.227 | 1.22715 | 155610 |
| 2026-04-23T00:00:00+00:00 | 1.22715 | 1.22835 | 1.22361 | 1.22502 | 446836 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T00:00:00+00:00 | 1.19902 | 1.20198 | 1.19684 | 1.19684 | 144274 |
| 2026-07-28T00:00:00+00:00 | 1.19684 | 1.20067 | 1.19547 | 1.19876 | 126070 |
| 2026-07-29T00:00:00+00:00 | 1.19876 | 1.20725 | 1.1976 | 1.20644 | 191278 |
| 2026-07-30T00:00:00+00:00 | 1.20644 | 1.21383 | 1.20357 | 1.21284 | 234128 |
| 2026-07-31T00:00:00+00:00 | 1.21284 | 1.21325 | 1.20567 | 1.20731 | 123248 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EURUSD_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURUSD_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('EURUSD_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **EURUSD** archive on **[getdata.finance](https://getdata.finance/datasets/eurusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **6,731** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)**

---
*GetData · EURUSD 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurusd) · 2026-08-05 UTC*

# EURUSD 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_651_338_rows-blue)](https://getdata.finance/datasets/eurusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurusd)

### -> [**Download the full EURUSD dataset on getdata.finance**](https://getdata.finance/datasets/eurusd)

**EURUSD 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **Euro / US Dollar**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **Euro / US Dollar** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurusd) · **1,651,338** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `EURUSD_1m.csv` (187,198 rows, `2026-02-01` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurusd)** — **1,651,338** `1m` rows (~154.20 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `2022-02-27` -> `2026-07-30`.

## Download sample

**[EURUSD_1m.csv](https://github.com/getdata-finance/eurusd-1m-ohlcv-forex-historical-data/blob/main/EURUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurusd-1m-ohlcv-forex-historical-data/main/EURUSD_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurusd-1m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurusd-1m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurusd-1m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurusd](https://getdata.finance/datasets/eurusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurusd))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 187,198 | **1,651,338** |
| Size | 17.21 MB | ~154.20 MB |
| Period | `2026-02-01` -> `2026-07-31` | `2022-02-27` -> `2026-07-30` |
| File | `EURUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Coverage report | — | [EURUSD coverage](https://getdata.finance/coverage/eurusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/eurusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-01T22:00:00+00:00 | 1.18439 | 1.18439 | 1.18409 | 1.18409 | 1 |
| 2026-02-01T22:01:00+00:00 | 1.18409 | 1.18409 | 1.18409 | 1.18409 | 2.2372276548 |
| 2026-02-01T22:02:00+00:00 | 1.18409 | 1.18409 | 1.18409 | 1.18409 | 1.1269660203 |
| 2026-02-01T22:03:00+00:00 | 1.18409 | 1.18419 | 1.18409 | 1.18419 | 1 |
| 2026-02-01T22:04:00+00:00 | 1.18419 | 1.18419 | 1.18419 | 1.18419 | 1.1034012678 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T20:54:00+00:00 | 1.16574 | 1.16622 | 1.16541 | 1.1661 | 505 |
| 2026-07-31T20:55:00+00:00 | 1.1661 | 1.1662 | 1.16582 | 1.16584 | 576 |
| 2026-07-31T20:56:00+00:00 | 1.16584 | 1.16625 | 1.16494 | 1.16524 | 562 |
| 2026-07-31T20:57:00+00:00 | 1.16524 | 1.1653 | 1.16496 | 1.16504 | 290 |
| 2026-07-31T20:58:00+00:00 | 1.16504 | 1.16523 | 1.16492 | 1.16492 | 186 |

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

df = pd.read_csv('EURUSD_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURUSD_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EURUSD_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **EURUSD** archive on **[getdata.finance](https://getdata.finance/datasets/eurusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,651,338** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)**

---
*GetData · EURUSD 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurusd) · 2026-08-04 UTC*

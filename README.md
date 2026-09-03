# EURUSD 1m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_685_501_rows-blue)](https://getdata.finance/datasets/eurusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurusd)

### -> [**Download the full EURUSD dataset on getdata.finance**](https://getdata.finance/datasets/eurusd)

**EURUSD 1m OHLCV forex historical data** — ultra high-quality 1m OHLCV for **Euro / US Dollar**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Euro / US Dollar** (Forex)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurusd) · **1,685,501** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `EURUSD_1m.csv` (55,440 rows, `2026-07-09` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurusd)** — **1,685,501** `1m` rows, **11 timeframes**, `2022-02-27` -> `2026-09-02`.

## Download sample

**[EURUSD_1m.csv](https://github.com/getdata-finance/eurusd-1m-ohlcv-forex-historical-data/blob/main/EURUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurusd-1m-ohlcv-forex-historical-data/main/EURUSD_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurusd))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **1,685,501** |
| Period | `2026-07-09` -> `2026-09-02` | `2022-02-27` -> `2026-09-02` |
| File | `EURUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Coverage report | — | [EURUSD coverage](https://getdata.finance/coverage/eurusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:49:00+00:00 | 1.15512 | 1.15527 | 1.15507 | 1.15522 | 168 |
| 2026-07-09T13:50:00+00:00 | 1.15522 | 1.15526 | 1.15509 | 1.15517 | 208 |
| 2026-07-09T13:51:00+00:00 | 1.15517 | 1.15536 | 1.15517 | 1.15526 | 203 |
| 2026-07-09T13:52:00+00:00 | 1.15526 | 1.15531 | 1.1551 | 1.1552 | 249 |
| 2026-07-09T13:53:00+00:00 | 1.1552 | 1.15523 | 1.15515 | 1.15516 | 159 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 1.15785 | 1.15785 | 1.15774 | 1.15774 | 47 |
| 2026-09-02T01:57:00+00:00 | 1.15774 | 1.15776 | 1.15774 | 1.15775 | 41 |
| 2026-09-02T01:58:00+00:00 | 1.15775 | 1.15782 | 1.15771 | 1.15781 | 67 |
| 2026-09-02T01:59:00+00:00 | 1.15781 | 1.15792 | 1.1578 | 1.15789 | 77 |
| 2026-09-02T02:00:00+00:00 | 1.15789 | 1.1579 | 1.15781 | 1.15781 | 63 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full EURUSD archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)**

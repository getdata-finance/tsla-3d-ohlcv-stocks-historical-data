# TSLA 3d OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_769_rows-blue)](https://getdata.finance/datasets/tsla) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/tsla)

### -> [**Download the full TSLA dataset on getdata.finance**](https://getdata.finance/datasets/tsla)

**TSLA 3d OHLCV stocks historical data** — ultra high-quality 3d OHLCV for **Tesla**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **Tesla** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/tsla) · **1,769** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `TSLA_3d.csv` (68 rows, `2026-02-09` -> `2026-09-01`, 4.15 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/tsla)** — **1,769** `3d` rows (full `1m`: 617,080), **11 timeframes**, `2010-06-27` -> `2026-09-01`.

## Download sample

**[TSLA_3d.csv](https://github.com/getdata-finance/tsla-3d-ohlcv-stocks-historical-data/blob/main/TSLA_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/tsla-3d-ohlcv-stocks-historical-data/main/TSLA_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/tsla-3d-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/tsla-3d-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/tsla-3d-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/tsla](https://getdata.finance/datasets/tsla)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/tsla))** |
|---|--:|---|
| Instrument | Tesla · US stocks | Tesla · US stocks |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 68 | **1,769** |
| Size | 4.15 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Period | `2026-02-09` -> `2026-09-01` | `2010-06-27` -> `2026-09-01` |
| File | `TSLA_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Coverage report | — | [TSLA coverage](https://getdata.finance/coverage/tsla) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/tsla)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/tsla) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`TSLA_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-09T00:00:00+00:00 | 410.75 | 436.05 | 407.17 | 428.14 | 272834 |
| 2026-02-12T00:00:00+00:00 | 428.14 | 435.99 | 410.76 | 417.55 | 389639 |
| 2026-02-15T00:00:00+00:00 | 417.55 | 417.55 | 400.39 | 410.38 | 152216 |
| 2026-02-18T00:00:00+00:00 | 410.38 | 416.74 | 403.99 | 411.66 | 465955 |
| 2026-02-21T00:00:00+00:00 | 411.66 | 411.66 | 393.92 | 399.67 | 109472 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 350.79 | 366.34 | 338.82 | 362.96 | 125730 |
| 2026-08-23T00:00:00+00:00 | 362.96 | 362.96 | 348.15 | 352.01 | 95652 |
| 2026-08-26T00:00:00+00:00 | 350.3 | 358.56 | 342.39 | 348.44 | 101484 |
| 2026-08-29T00:00:00+00:00 | 348.44 | 368.74 | 346.75 | 367.7 | 67125 |
| 2026-09-01T00:00:00+00:00 | 367.7 | 367.7 | 352.84 | 356.09 | 46510 |

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

df = pd.read_csv('TSLA_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('TSLA_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('TSLA_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **TSLA** archive on **[getdata.finance](https://getdata.finance/datasets/tsla)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,769** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full TSLA dataset on getdata.finance](https://getdata.finance/datasets/tsla)**

---
*GetData · TSLA 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/tsla)*

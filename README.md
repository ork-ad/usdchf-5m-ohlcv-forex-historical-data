# USDCHF 5m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_815_429_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full USDCHF dataset on ork.ad**](https://ork.ad/)

**USDCHF 5m OHLCV Forex historical data** — ultra high-quality 5m OHLCV for **US Dollar / Swiss Franc**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **US Dollar / Swiss Franc** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **1,815,429** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `USDCHF_5m.csv` (37,235 rows, `2026-01-04` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **1,815,429** `5m` rows (~95.98 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2001-11-28` → `2026-07-03`.

## Download sample

**[USDCHF_5m.csv](https://github.com/ork-ad/usdchf-5m-ohlcv-forex-historical-data/blob/main/USDCHF_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usdchf-5m-ohlcv-forex-historical-data/main/USDCHF_5m.csv)) · [GitHub Releases](https://github.com/ork-ad/usdchf-5m-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usdchf-5m-ohlcv-forex-historical-data/](https://ork-ad.github.io/usdchf-5m-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | US Dollar / Swiss Franc · Forex | US Dollar / Swiss Franc · Forex |
| Timeframes | `5m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 5m rows | 37,235 | **1,815,429** |
| Size | 2.04 MB | ~95.98 MB |
| Period | `2026-01-04` → `2026-07-03` | `2001-11-28` → `2026-07-03` |
| File | `USDCHF_5m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`5m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `5m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCHF_5m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T22:05:00Z | 0.79192 | 0.79192 | 0.79099 | 0.79135 | 24 |
| 2026-01-04T22:10:00Z | 0.79135 | 0.79147 | 0.79092 | 0.79104 | 84 |
| 2026-01-04T22:15:00Z | 0.79104 | 0.79175 | 0.79024 | 0.791589151 | 169 |
| 2026-01-04T22:20:00Z | 0.791589151 | 0.791589151 | 0.7914 | 0.7914 | 5 |
| 2026-01-04T22:25:00Z | 0.7914 | 0.79166 | 0.79116 | 0.79166 | 54 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T20:35:00Z | 0.8039 | 0.8039 | 0.80361 | 0.80376 | 578 |
| 2026-07-03T20:40:00Z | 0.80376 | 0.80382 | 0.80376 | 0.8038 | 116 |
| 2026-07-03T20:45:00Z | 0.8038 | 0.8039 | 0.80377 | 0.80387 | 263 |
| 2026-07-03T20:50:00Z | 0.80387 | 0.8039 | 0.80354 | 0.80354 | 116 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDCHF_5m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCHF_5m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('USDCHF_5m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **USDCHF** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **1,815,429** rows at `5m`, plus all other timeframes in the same ZIP.

**[→ Get the full USDCHF dataset on ork.ad](https://ork.ad/)**

---
*GetData · USDCHF 5m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*
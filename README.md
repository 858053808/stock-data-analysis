# US Stock Data Analysis

This repository contains analysis of US stocks ranked by average trading volume and dollar amount.

## Data Source

Data sourced from **Perplexity Finance** as of January 29, 2026.

## Files

### `top_200_stocks_by_volume.csv`

Top US stocks filtered by average trading dollar volume over the past 6 months (August 2025 - January 2026).

**Columns:**
- `Rank`: Ranking by average trading dollar volume
- `Ticker`: Stock ticker symbol
- `Company`: Company name
- `Exchange`: Stock exchange (NASDAQ, NYSE, AMEX)
- `Price`: Current stock price (as of Jan 29, 2026)
- `Current_Volume`: Current trading volume
- `Avg_Volume_6M`: Average trading volume over 6 months
- `Avg_Trading_Dollar_Volume`: Average daily trading dollar volume (Price × Avg Volume)
- `Market_Cap_B`: Market capitalization in billions USD
- `52W_High`: 52-week high price
- `52W_Low`: 52-week low price
- `Change_Pct`: Percentage change

## Selection Criteria

✅ **Filter Applied:**
1. Top 200 US stocks by average trading dollar amount (past 6 months)

## Key Insights

**Top 3 Most Actively Traded Stocks:**
1. **NVDA** (NVIDIA) - $34.93B average daily dollar volume
2. **TSLA** (Tesla) - $32.19B average daily dollar volume
3. **META** (Meta Platforms) - $12.84B average daily dollar volume

**Market Leaders by Market Cap:**
- NVDA: $4.66T
- GOOGL: $4.05T
- AAPL: $3.79T
- MSFT: $3.58T

## Usage

You can use this data for:
- Financial analysis and research
- Trading volume analysis
- Portfolio construction
- Market trend analysis
- Statistical modeling

## Date Generated

January 29, 2026

## Data Quality

- Real-time market data from Perplexity Finance
- All values in USD
- Volume figures in millions (M) of shares

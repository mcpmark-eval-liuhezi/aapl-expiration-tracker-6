# AAPL Expiration Tracker

Weekly options review data for Apple Inc. (AAPL), pulled from live Yahoo Finance data.

Generated: 2026-11-10 (regular market close) · Share price used: **$348.51**

## Company Snapshot

| Field | Value |
| --- | --- |
| Ticker | AAPL |
| Company | Apple Inc. |
| Headquarters address | One Apple Park Way, Cupertino, CA 95014, United States |
| Sector | Technology |
| Industry | Consumer Electronics |
| Current share price | $348.51 |

## Option Expiration Dates Available (as returned by the source)

2026-11-11, 2026-11-13, 2026-11-16, 2026-11-18, 2026-11-20, 2026-11-27, 2026-12-04, 2026-12-11, 2026-12-18, 2026-12-24, 2027-01-15, 2027-02-19, 2027-03-19, 2027-04-16, 2027-06-17, 2027-09-17, 2027-12-17, 2028-01-21, 2028-03-17, 2028-06-16, 2028-12-15, 2029-01-19

## Per-Expiration Chain Stats

| Expiration | ATM Strike | Highest-OI Call | Highest-OI Call OI | Highest-OI Put | Highest-OI Put OI |
| --- | --- | --- | --- | --- | --- |
| 2026-11-11 | 347.50 | 355.00 | 32,028 | 340.00 | 3,922 |
| 2026-11-13 | 347.50 | 360.00 | 16,260 | 265.00 | 10,657 |
| 2026-11-16 | 347.50 | 355.00 | 5,171 | 340.00 | 1,025 |

### Method notes

- **Share price used:** $348.51 (regularMarketPrice / currentPrice from the live quote)
- **ATM strike:** the listed strike closest to the current share price
- **Call strike with highest open interest:** max open interest across all listed call strikes for that expiration
- **Put strike with highest open interest:** max open interest across all listed put strikes for that expiration

## Notes / Oddities flagged from the source

- `github_get_stock_info` reports `"tradeable": false` and standard bid/ask pairs with bid-size 4 / ask-size 5, while the last regular market quote and post-market quote (~$349.00) are returned normally — numbers reported here are exactly what the source returned.
- All OI figures come from Yahoo Finance option chains as returned on 2026-11-10; open interest was still shifting on the 2026-11-13 and 2026-11-16 expirations.

# Contributing

## Building weekly AAPL options reviews

1. Pull live market data (share price, expiration dates, option chains) from the data source.
2. Compute per-expiration stats: ATM strike (nearest listed strike to the current share price), highest open-interest call strike, and highest open-interest put strike.
3. Add tracking issues to this repo, one per expiration, dated in ascending order (e.g. `Expiry YYYY-MM-DD`).
4. Add/refresh `expirations.md` at the repo root with the company snapshot, the full expiration-date list, and the per-expiration stats table.
5. Open a pull request from a feature branch into `main`.

## Repo conventions

- Market figures must come from live data; where a number looks odd, report exactly what the source returned.
-窒
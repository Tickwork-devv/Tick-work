# Changelog

## 0.1.0 — initial release

- `ConstantProductPool` — x·y=k pool with quotes, swaps, slippage, fees
- `ClmmPool` — concentrated liquidity: tick math, ranged positions,
  cross-tick swaps with partial fills, fee accrual paid out on close
- 14 invariant tests covering the above
- Interactive site (`index.html`) with 7 sections, embedding the engine live
  and running the test suite in-browser

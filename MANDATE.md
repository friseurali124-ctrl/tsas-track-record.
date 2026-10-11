# Investment Mandate – TSAS (Trade Safe and Smart)

Manager: Luis-Enrico Wolthuis
Version: 1.0
Published: 2026-10-11
Start of trading: 2026-10-12
Duration: minimum of one year, open-ended thereafter

## 1. Objective
Achieve an absolute return of 25% p.a. net of costs, measured
time-weighted, and outperform the combined benchmark.
The maximum drawdown must never exceed 50%.

## 2. Benchmark
Combined benchmark: equal-weighted average of the annual (and
monthly) percentage returns of the S&P 500 and the DAX.

## 3. Capital and Account
- Starting capital: EUR 182,503.95
- Broker: Trade Republic
- Returns are calculated time-weighted (TWR). All deposits and
  withdrawals are logged with date and pre-flow account balance.

## 4. Investment Universe
Permitted:
- Call and put warrants on single stocks and ETFs, effective
  leverage up to 10. Long and short exposure are both taken
  deliberately: long via call warrants, short via put warrants.
- Direct positions in single stocks and ETFs.
Not permitted: knock-out certificates, futures, CFDs,
cryptocurrencies, direct short selling.

## 5. Strategy
Short-term, high-conviction swing trading on the daily chart,
combining a fundamental filter with a multi-indicator technical
setup. Large position sizes are used to capture small,
high-probability moves. See STRATEGY.md for details.

## 6. Position Sizing and Risk Rules
- Warrant position size: EUR 10,000 to 100,000 per trade.
- Profit taking: +1% to +50% on the position value.
- Exit on invalidation: there is no fixed stop loss and no time
  stop. A position is held as long as the setup remains valid
  and is closed as soon as it is invalidated (criteria defined
  in STRATEGY.md). Interim drawdowns of 30% or more on a single
  position are accepted while the setup remains valid.
- Maximum drawdown: 50% from the high-water mark of the account.
  When reached, all trading is paused for [e.g. 1 month] and the
  strategy is formally reviewed before resuming.

## 7. Known Risks
- No fixed stop: losses per position are limited only by the
  invalidation rules and can be substantial.
- A loss of 30% on a EUR 100,000 position equals approx. 16% of
  starting capital.
- Warrants move up to 10 times the underlying, so overnight gaps,
  spreads, issuer pricing and implied volatility can cause losses
  beyond what the underlying's move suggests.

## 8. Reporting
- Every trade is logged on the day it is opened and closed,
  including the reason for the exit.
- Monthly: net TWR return vs. S&P 500, DAX and the combined
  benchmark; factsheet; archived broker statement (kept offline).
- Annually: performance review including a mandate compliance check.

## 9. Amendments
Any change to this mandate is published as a new version with date
and rationale in CHANGELOG.md. Previous versions remain in the
git history.

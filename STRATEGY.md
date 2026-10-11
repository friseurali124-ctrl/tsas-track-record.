# Strategy Description – TSAS

## Philosophy
TSAS takes large positions to capture small, high-probability
moves. The aim is not to catch large trends, but to identify
setups where a 1–10% move in the underlying is highly likely,
and to amplify it with leveraged warrants. Many small,
disciplined wins form the edge. Positions are entered and
exited quickly, in both directions.

## 1. Fundamental Filter
Every candidate is screened with a proprietary TradingView screener
template covering 11 key financial ratios, plus the Piotroski
F-Score and the Altman Z-Score.
- Long candidates: positive operating cash flow, positive net
  margin, solid F-Score and Z-Score.
- Short candidates: fundamentals are weighted less, but the company
  must not be significantly undervalued.

## 2. Technical Framework
Monthly, weekly and daily charts are reviewed for context; all
indicators are applied on the daily chart.

Trend
- Moving averages: 10 EMA, 21, 50, 100, 150 and 200 MA, on daily
  and weekly charts, to identify breakouts, support and resistance.
- MACD: primary trigger.

Volatility
- Bollinger Bands and Bollinger BandWidth
- ATR
Low BandWidth signals compression ahead of a strong directional
move. High BandWidth signals stretched conditions suited for
recovery moves.

Volume
- On-Balance Volume (OBV), including divergences
- Money Flow Index (MFI)

Directional strength
- DMI (+DI / −DI) to confirm whether buyers or sellers dominate.

Sentiment
- Put/Call Ratio, VIX, Fear & Greed Index

## 3. Entry Rules
Long (call warrant):
1. Fundamental filter passed.
2. Bullish MACD cross on the daily chart.
3. Volatility regime fits the setup (low BandWidth for breakouts,
   high BandWidth for recovery moves).
4. OBV and DMI confirm buying pressure, backed by volume.
5. Price at a breakout or support level defined by the MAs.

Short (put warrant):
1. Company not significantly undervalued.
2. Bearish MACD cross on the daily chart.
3. Volatility regime fits the setup.
4. OBV and DMI confirm selling pressure, backed by volume.
   Typical pattern: price moves sideways while OBV falls sharply
   and BandWidth is at very low levels, signalling a likely
   breakdown.
5. Price at a breakdown or resistance level defined by the MAs.

## 4. Instrument Selection
Warrants with effective leverage up to 10, chosen so that the
expected 1–5% move in the underlying translates into a
5–50% gain on the position.

## 5. Exit Rules
Profit: positions are closed between +5% and +50%, often early
once the expected move has played out.

Invalidation: a position is closed when the setup that justified
the entry no longer holds, in particular when:
- price falls significantly back through the breakout level or
  the relevant MAs (or rises back above them for shorts) and
  fails to reclaim them, and
- volume (OBV, MFI) and directional strength (DMI) turn against
  the position, and/or
- the MACD signal reverses.
There is no fixed stop loss and no time stop. The reason for every
exit is documented in the trade journal.

## 6. Discretion
Deviations from these rules must be justified in the trade
journal (column "Rules_Followed" = No).

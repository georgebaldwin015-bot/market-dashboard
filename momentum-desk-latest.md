# Edge Lab — Daily Report (2026-09-30)
*Educational/informational output modeling Mark Minervini's and Kristjan "Qullamaggie" Kullamägi's publicly
described methodologies. Not personalized financial advice; this is not a licensed advisor. Confirm every
setup on an actual chart before acting.*
*Data source: Yahoo Finance (via yfinance), end-of-day bars. Universe defined in `universe.csv` — edit that file to expand coverage. Sector/industry groupings are derived live from Yahoo Finance and shared with the Daily Market Report tab via `industry_map.py`.*
## What's Going On

The market is in a confirmed uptrend, with breadth reading 26% of the scanned universe above its 50-day moving average and 9 distribution days in the past month -- an elevated count worth watching. Zooming out, breadth has been deteriorating over the last 60 sessions (-43.0 pt change in % above the 50-day MA) and deteriorating over the last two weeks (-9.3 pt), while SPY is climbing (+2.2% over 60 sessions, +1.3% over the last two weeks). That's a narrow-leadership divergence worth flagging -- SPY's recent climb isn't being confirmed by broader participation. Momentum under the surface is leaning short -- 11 name(s) hit a fresh 52-week high today against 32 breaking down to a fresh 52-week low. Health Care is leading, with 60% of its 60 scanned names carrying an RS score of 70+ and 19 clearing a screen outright today, with Energy also showing real strength. It's being driven by names like MRNA, CRL and HUM. With 68 name(s) clearing a screen across 10 sector(s), there's a workable watchlist below -- see Worth Watching for the shortlist tied to today's regime and themes.

## 1. Market Pulse

Market cycle: **Bull** -- equal-weight universe index +2.2% vs its 200-day MA, 50-day MA +6.6% vs the 200-day. Trade normally.

SPY close: 765.61 | 10-day MA: 764.89 | 20-day MA: 763.93

**Constructive** — 10-day MA above the 20-day and rising. Long setups get the benefit of the doubt.

- Breadth: 26% of the scanned universe above its 50-day MA, 47% above its 200-day MA.
- 52-week breakouts vs breakdowns today: 11 breakouts / 32 breakdowns (out of 518 names evaluated).
- Distribution days (SPY, trailing 25 sessions): 9. Elevated -- a headwind even if price is holding up.
- Follow-through day: none in the recent window.

## 2. Leading Themes

Ranked by breadth of strength (share of each sector's names with an RS score >= 70), not raw average price change -- see Risk & Process Notes.

| Sector | Names Scanned | Median RS | % RS >= 70 | Clearing a Screen |
|---|---|---|---|---|
| Health Care | 60 | 75 | 60% | 19 |
| Energy | 21 | 74 | 57% | 7 |
| Information Technology | 90 | 78 | 57% | 29 |
| Industrials | 79 | 46 | 28% | 10 |
| Materials | 26 | 54 | 23% | 4 |
| Communication Services | 22 | 50 | 18% | 1 |
| Consumer Staples | 31 | 46 | 16% | 3 |
| Financials | 70 | 50 | 16% | 1 |
| Consumer Discretionary | 53 | 26 | 11% | 2 |
| Real Estate | 29 | 39 | 10% | 0 |
| Utilities | 31 | 23 | 0% | 1 |
| Unknown | 3 | 6 | 0% | 0 |

**Leading theme: Health Care** — 60% of its 60 scanned names carry an RS score of 70+, and 19 name(s) are clearing a screen outright today.

## 3. Leading Stocks

**Leader spotlight** — the strongest names driving today's leading themes:

- **MRNA** (Health Care) — RS 99.0, VCP contraction (watch for trigger) [Flag-Watch], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MU** (Information Technology) — RS 99.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MU)
- **INTC** (Information Technology) — RS 98.0, VCP contraction (watch for trigger) [Flag-Watch], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=INTC)

**Health Care** (18)

### MRNA — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 198.88
- Entry: pivot 198.88 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 7.0% | RS score: 99.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 99.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 7.0% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CRL — Health Care [chart](https://www.tradingview.com/chart/?symbol=CRL)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.95x avg, needs 1.5x)
- Pivot (breakout trigger level): 294.44
- Entry: next session's open, only if volume confirms (price is already above pivot 294.44 on light volume)
- Volume vs 50-day avg: 0.95x
- ADR%: 3.2% | RS score: 95.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 95.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HUM — Health Care [chart](https://www.tradingview.com/chart/?symbol=HUM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 409.8
- Entry: pivot 409.8 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.28x
- ADR%: 3.4% | RS score: 94.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 94.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### RVTY — Health Care [chart](https://www.tradingview.com/chart/?symbol=RVTY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 151.11
- Entry: pivot 151.11 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 3.4% | RS score: 94.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 94.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VTRS — Health Care [chart](https://www.tradingview.com/chart/?symbol=VTRS)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.33x avg, needs 1.5x)
- Pivot (breakout trigger level): 17.83
- Entry: next session's open, only if volume confirms (price is already above pivot 17.83 on light volume)
- Volume vs 50-day avg: 1.33x
- ADR%: 2.4% | RS score: 93.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 93.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MRK — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRK)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 151.45
- Entry: pivot 151.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 2.1% | RS score: 91.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 91.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WST — Health Care [chart](https://www.tradingview.com/chart/?symbol=WST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 375.87
- Entry: pivot 375.87 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
- ADR%: 2.3% | RS score: 89.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 89.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AMGN — Health Care [chart](https://www.tradingview.com/chart/?symbol=AMGN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 444.12
- Entry: pivot 444.12 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.04x
- ADR%: 2.2% | RS score: 88.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 88.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DXCM — Health Care [chart](https://www.tradingview.com/chart/?symbol=DXCM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 91.06
- Entry: pivot 91.06 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 2.5% | RS score: 88.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 88.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### BIIB — Health Care [chart](https://www.tradingview.com/chart/?symbol=BIIB)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.46x avg, needs 1.5x)
- Pivot (breakout trigger level): 227.6
- Entry: next session's open, only if volume confirms (price is already above pivot 227.6 on light volume)
- Volume vs 50-day avg: 1.46x
- ADR%: 2.5% | RS score: 87.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 87.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### INCY — Health Care [chart](https://www.tradingview.com/chart/?symbol=INCY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 128.83
- Entry: pivot 128.83 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 2.6% | RS score: 86.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 86.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### GILD — Health Care [chart](https://www.tradingview.com/chart/?symbol=GILD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 152.67
- Entry: pivot 152.67 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.82x
- ADR%: 2.2% | RS score: 84.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 84.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### JNJ — Health Care [chart](https://www.tradingview.com/chart/?symbol=JNJ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 278.43
- Entry: pivot 278.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.06x
- ADR%: 1.8% | RS score: 83.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 83.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DGX — Health Care [chart](https://www.tradingview.com/chart/?symbol=DGX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 247.45
- Entry: pivot 247.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.99x
- ADR%: 2.3% | RS score: 83.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 83.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### BDX — Health Care [chart](https://www.tradingview.com/chart/?symbol=BDX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 188.41
- Entry: pivot 188.41 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.04x
- ADR%: 2.1% | RS score: 82.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 82.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### LLY — Health Care [chart](https://www.tradingview.com/chart/?symbol=LLY)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.78x avg, needs 1.5x)
- Pivot (breakout trigger level): 1183.46
- Entry: next session's open, only if volume confirms (price is already above pivot 1183.46 on light volume)
- Volume vs 50-day avg: 0.78x
- ADR%: 2.3% | RS score: 80.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 80.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ABBV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ABBV)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.95x avg, needs 1.5x)
- Pivot (breakout trigger level): 265.21
- Entry: next session's open, only if volume confirms (price is already above pivot 265.21 on light volume)
- Volume vs 50-day avg: 0.95x
- ADR%: 1.9% | RS score: 75.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 75.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VRTX — Health Care [chart](https://www.tradingview.com/chart/?symbol=VRTX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 557.96
- Entry: pivot 557.96 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.1% | RS score: 75.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 75.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Energy** (7)

### VLO — Energy [chart](https://www.tradingview.com/chart/?symbol=VLO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 413.28
- Entry: pivot 413.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.15x
- ADR%: 4.0% | RS score: 97.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 97.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.0% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MPC — Energy [chart](https://www.tradingview.com/chart/?symbol=MPC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 424.89
- Entry: pivot 424.89 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.0x
- ADR%: 3.7% | RS score: 96.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 96.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### PSX — Energy [chart](https://www.tradingview.com/chart/?symbol=PSX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 274.21
- Entry: pivot 274.21 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.21x
- ADR%: 3.2% | RS score: 95.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 95.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### APA — Energy [chart](https://www.tradingview.com/chart/?symbol=APA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 47.41
- Entry: pivot 47.41 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.4x
- ADR%: 3.0% | RS score: 92.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 92.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: no
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CVX — Energy [chart](https://www.tradingview.com/chart/?symbol=CVX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 217.77
- Entry: pivot 217.77 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.09x
- ADR%: 1.9% | RS score: 84.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 84.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### XOM — Energy [chart](https://www.tradingview.com/chart/?symbol=XOM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 169.32
- Entry: pivot 169.32 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 2.0% | RS score: 84.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 84.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DVN — Energy [chart](https://www.tradingview.com/chart/?symbol=DVN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.33
- Entry: pivot 51.33 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.6% | RS score: 74.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 74.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

**Information Technology** (26)

### MU — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MU)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1096.16
- Entry: pivot 1096.16 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 3.8% | RS score: 99.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 99.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### INTC — Information Technology [chart](https://www.tradingview.com/chart/?symbol=INTC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 127.39
- Entry: pivot 127.39 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.03x
- ADR%: 4.6% | RS score: 98.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 98.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.6% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### LITE — Information Technology [chart](https://www.tradingview.com/chart/?symbol=LITE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 988.98
- Entry: pivot 988.98 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.95x
- ADR%: 5.9% | RS score: 98.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 98.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 5.9% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AMD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AMD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 630.63
- Entry: pivot 630.63 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 3.7% | RS score: 98.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 98.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### DELL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=DELL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 588.4
- Entry: pivot 588.4 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
- ADR%: 5.9% | RS score: 98.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 98.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 5.9% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### STX — Information Technology [chart](https://www.tradingview.com/chart/?symbol=STX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 923.12
- Entry: pivot 923.12 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.76x
- ADR%: 5.2% | RS score: 98.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 98.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 5.2% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PANW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PANW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 393.3
- Entry: pivot 393.3 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.96x
- ADR%: 4.8% | RS score: 97.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 97.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.8% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CRWD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 262.49
- Entry: pivot 262.49 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 5.1% | RS score: 97.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 97.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 5.1% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### MRVL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MRVL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 262.36
- Entry: pivot 262.36 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 4.4% | RS score: 97.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 97.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.4% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### HPE — Information Technology [chart](https://www.tradingview.com/chart/?symbol=HPE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 63.52
- Entry: pivot 63.52 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 5.9% | RS score: 97.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 97.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 5.9% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DDOG — Information Technology [chart](https://www.tradingview.com/chart/?symbol=DDOG)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.8x avg, needs 1.5x)
- Pivot (breakout trigger level): 268.13
- Entry: next session's open, only if volume confirms (price is already above pivot 268.13 on light volume)
- Volume vs 50-day avg: 0.8x
- ADR%: 4.7% | RS score: 96.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 96.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.7% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FTNT — Information Technology [chart](https://www.tradingview.com/chart/?symbol=FTNT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 178.74
- Entry: pivot 178.74 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.59x
- ADR%: 3.9% | RS score: 96.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 96.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.9% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### NTAP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.23x avg, needs 1.5x)
- Pivot (breakout trigger level): 201.15
- Entry: next session's open, only if volume confirms (price is already above pivot 201.15 on light volume)
- Volume vs 50-day avg: 1.23x
- ADR%: 4.3% | RS score: 95.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 95.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.3% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### TER — Information Technology [chart](https://www.tradingview.com/chart/?symbol=TER)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.69x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 398.69
- Entry: next session's open, only if volume confirms (price is already above pivot 398.69 on light volume)
- Volume vs 50-day avg: 0.69x
- ADR%: 4.1% | RS score: 95.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 95.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.1% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### ZBRA — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ZBRA)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.9x avg, needs 1.5x)
- Pivot (breakout trigger level): 371.02
- Entry: next session's open, only if volume confirms (price is already above pivot 371.02 on light volume)
- Volume vs 50-day avg: 0.9x
- ADR%: 2.9% | RS score: 94.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 94.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### KEYS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=KEYS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 362.15
- Entry: pivot 362.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.7x
- ADR%: 2.6% | RS score: 93.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 93.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ANET — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ANET)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 206.55
- Entry: pivot 206.55 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.56x
- ADR%: 3.2% | RS score: 93.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 93.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### HPQ — Information Technology [chart](https://www.tradingview.com/chart/?symbol=HPQ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 35.48
- Entry: pivot 35.48 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.85x
- ADR%: 4.8% | RS score: 92.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 92.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.8% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: no
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### ASML — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ASML)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.99x avg, needs 1.5x)
- Pivot (breakout trigger level): 1764.85
- Entry: next session's open, only if volume confirms (price is already above pivot 1764.85 on light volume)
- Volume vs 50-day avg: 0.99x
- ADR%: 2.3% | RS score: 91.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 91.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FFIV — Information Technology [chart](https://www.tradingview.com/chart/?symbol=FFIV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 455.99
- Entry: pivot 455.99 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 3.3% | RS score: 90.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 90.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SWKS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=SWKS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 91.45
- Entry: pivot 91.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.52x
- ADR%: 6.0% | RS score: 90.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 90.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 6.0% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### GRMN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=GRMN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 295.04
- Entry: pivot 295.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.75x
- ADR%: 2.3% | RS score: 89.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 89.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### TXN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=TXN)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.74x avg, needs 1.5x)
- Pivot (breakout trigger level): 278.07
- Entry: next session's open, only if volume confirms (price is already above pivot 278.07 on light volume)
- Volume vs 50-day avg: 0.74x
- ADR%: 2.7% | RS score: 89.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 89.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AAPL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AAPL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 341.07
- Entry: pivot 341.07 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.2% | RS score: 86.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 86.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### NVDA — Information Technology [chart](https://www.tradingview.com/chart/?symbol=NVDA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 230.1
- Entry: pivot 230.1 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.17x
- ADR%: 2.2% | RS score: 85.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 85.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### APH — Information Technology [chart](https://www.tradingview.com/chart/?symbol=APH)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.11x avg, needs 1.5x)
- Pivot (breakout trigger level): 84.09
- Entry: next session's open, only if volume confirms (price is already above pivot 84.09 on light volume)
- Volume vs 50-day avg: 1.11x
- ADR%: 3.0% | RS score: 80.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 80.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Industrials** (9)

### EXPD — Industrials [chart](https://www.tradingview.com/chart/?symbol=EXPD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 193.9
- Entry: pivot 193.9 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 2.0% | RS score: 89.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 89.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DE — Industrials [chart](https://www.tradingview.com/chart/?symbol=DE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 709.48
- Entry: pivot 709.48 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 2.3% | RS score: 88.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 88.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### NDSN — Industrials [chart](https://www.tradingview.com/chart/?symbol=NDSN)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.0x avg, needs 1.5x)
- Pivot (breakout trigger level): 325.77
- Entry: next session's open, only if volume confirms (price is already above pivot 325.77 on light volume)
- Volume vs 50-day avg: 1.0x
- ADR%: 1.7% | RS score: 87.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 87.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WAB — Industrials [chart](https://www.tradingview.com/chart/?symbol=WAB)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.86x avg, needs 1.5x)
- Pivot (breakout trigger level): 292.23
- Entry: next session's open, only if volume confirms (price is already above pivot 292.23 on light volume)
- Volume vs 50-day avg: 0.86x
- ADR%: 2.0% | RS score: 85.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 85.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### IEX — Industrials [chart](https://www.tradingview.com/chart/?symbol=IEX)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.08x avg, needs 1.5x)
- Pivot (breakout trigger level): 230.28
- Entry: next session's open, only if volume confirms (price is already above pivot 230.28 on light volume)
- Volume vs 50-day avg: 1.08x
- ADR%: 1.8% | RS score: 81.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 81.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EMR — Industrials [chart](https://www.tradingview.com/chart/?symbol=EMR)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.83x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 158.23
- Entry: next session's open, only if volume confirms (price is already above pivot 158.23 on light volume)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.2% | RS score: 78.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 78.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### AME — Industrials [chart](https://www.tradingview.com/chart/?symbol=AME)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.04x avg, needs 1.5x)
- Pivot (breakout trigger level): 250.74
- Entry: next session's open, only if volume confirms (price is already above pivot 250.74 on light volume)
- Volume vs 50-day avg: 1.04x
- ADR%: 1.9% | RS score: 77.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 77.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### JCI — Industrials [chart](https://www.tradingview.com/chart/?symbol=JCI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 150.2
- Entry: pivot 150.2 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.94x
- ADR%: 2.0% | RS score: 77.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 77.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ETN — Industrials [chart](https://www.tradingview.com/chart/?symbol=ETN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 442.49
- Entry: pivot 442.49 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.11x
- ADR%: 2.7% | RS score: 76.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 76.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Materials** (2)

### FCX — Materials [chart](https://www.tradingview.com/chart/?symbol=FCX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 76.62
- Entry: pivot 76.62 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.67x
- ADR%: 3.2% | RS score: 92.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 92.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### IFF — Materials [chart](https://www.tradingview.com/chart/?symbol=IFF)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 87.54
- Entry: pivot 87.54 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.13x
- ADR%: 1.8% | RS score: 85.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 85.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Communication Services** (1)

### NBIS — Communication Services [chart](https://www.tradingview.com/chart/?symbol=NBIS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 243.88
- Entry: pivot 243.88 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.61x
- ADR%: 6.2% | RS score: 96.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 96.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 6.2% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Consumer Staples** (2)

### KO — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 89.13
- Entry: pivot 89.13 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.94x
- ADR%: 1.3% | RS score: 77.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 77.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.3% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: no
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=PM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 194.86
- Entry: pivot 194.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.86x
- ADR%: 2.2% | RS score: 73.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 73.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Financials** (1)

### PFG — Financials [chart](https://www.tradingview.com/chart/?symbol=PFG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 118.51
- Entry: pivot 118.51 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.97x
- ADR%: 2.2% | RS score: 85.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 85.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Consumer Discretionary** (2)

### TGT — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=TGT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 164.44
- Entry: pivot 164.44 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
- ADR%: 2.2% | RS score: 94.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 94.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### BBY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=BBY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 94.82
- Entry: pivot 94.82 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
- ADR%: 3.4% | RS score: 88.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 8/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 88.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>


## 4. Worth Watching

Market regime reads **constructive**, and **Health Care** is leading with 60% of its names carrying RS 70+ and 19 clearing a screen outright today. On that basis, these 8 name(s) are worth watching:

- **MRNA** (Health Care) — VCP contraction (watch for trigger) [Flag-Watch], RS 99.0, pivot 198.88. Entry: pivot 198.88 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MU** (Information Technology) — VCP contraction (watch for trigger), RS 99.0, pivot 1096.16. Entry: pivot 1096.16 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MU)
- **INTC** (Information Technology) — VCP contraction (watch for trigger) [Flag-Watch], RS 98.0, pivot 127.39. Entry: pivot 127.39 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=INTC)
- **LITE** (Information Technology) — VCP contraction (watch for trigger), RS 98.0, pivot 988.98. Entry: pivot 988.98 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=LITE)
- **AMD** (Information Technology) — VCP contraction (watch for trigger) [Flag-Watch], RS 98.0, pivot 630.63. Entry: pivot 630.63 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=AMD)
- **DELL** (Information Technology) — VCP contraction (watch for trigger) [VCP-Watch], RS 98.0, pivot 588.4. Entry: pivot 588.4 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=DELL)
- **STX** (Information Technology) — VCP contraction (watch for trigger), RS 98.0, pivot 923.12. Entry: pivot 923.12 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=STX)
- **VLO** (Energy) — VCP contraction (watch for trigger), RS 97.0, pivot 413.28. Entry: pivot 413.28 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=VLO)

## 5. Other Setups (context)


**Extended / parabolic-short context (not a trade signal by itself):**
- MRNA (Health Care) [chart](https://www.tradingview.com/chart/?symbol=MRNA) — 74.9% above 50-day MA, +34.5% over the last 10 sessions.

## 6. Names to Avoid / Under Distribution

No prior leaders showing a clear technical breakdown flagged today.

## 7. Risk & Process Notes
- Universe scanned: 520 tickers.
- Minervini stop discipline: ~7-8% max below entry, sized to keep account risk small.
- Qullamaggie stop discipline: stop within ~1x ADR of entry; risk ~0.25-1% of account per trade.
- VCP/staging flags are rule-based approximations of a visual pattern — confirm on the linked TradingView chart.
- Leading Themes is ranked by breadth of RS strength, not raw average price change, so it isn't skewed by one outlier name in an otherwise quiet sector.
- Breadth, distribution-day, and follow-through-day stats are simplified approximations of IBD's own methodology, computed from the same price history already pulled for this run — directional signal, not an exact replica.
- If the Market Pulse section above reads "Defensive," treat every long breakout here as lower-probability.

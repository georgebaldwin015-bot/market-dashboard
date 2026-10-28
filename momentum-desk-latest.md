# Edge Lab — Daily Report (2026-10-28)
*Educational/informational output modeling Mark Minervini's and Kristjan "Qullamaggie" Kullamägi's publicly
described methodologies. Not personalized financial advice; this is not a licensed advisor. Confirm every
setup on an actual chart before acting.*
*Data source: Yahoo Finance (via yfinance), end-of-day bars. Universe defined in `universe.csv` — edit that file to expand coverage. Sector/industry groupings are derived live from Yahoo Finance and shared with the Daily Market Report tab via `industry_map.py`.*
## What's Going On

The market is in a defensive posture, with breadth reading 61% of the scanned universe above its 50-day moving average and 6 distribution days in the past month -- an elevated count worth watching. Zooming out, breadth has been deteriorating over the last 60 sessions (-7.7 pt change in % above the 50-day MA) and improving over the last two weeks (+25.7 pt), while SPY is roughly flat (+0.0% over 60 sessions, +0.0% over the last two weeks). Momentum under the surface is leaning long -- 16 name(s) hit a fresh 52-week high today against 13 breaking down to a fresh 52-week low. Energy is leading, with 71% of its 21 scanned names carrying an RS score of 70+ and 14 clearing a screen outright today, with Information Technology also showing real strength. It's being driven by names like MPC, PSX and APA. With 93 name(s) clearing a screen across 11 sector(s), there's a workable watchlist below -- see Worth Watching for the shortlist tied to today's regime and themes.

## 1. Market Pulse

Market cycle: **Bull** -- equal-weight universe index +6.2% vs its 200-day MA, 50-day MA +4.8% vs the 200-day. Trade normally.

SPY close: 769.66 | 10-day MA: 767.22 | 20-day MA: 770.41

**Defensive** — 10-day MA below the 20-day. Setups that still pass the rules here averaged a little less (+0.5R vs +0.7R a trade) but skipping them cut the backtest's return: trade the plan.

- Breadth: 61% of the scanned universe above its 50-day MA, 61% above its 200-day MA.
- 52-week breakouts vs breakdowns today: 16 breakouts / 13 breakdowns (out of 519 names evaluated).
- Distribution days (SPY, trailing 25 sessions): 6. Elevated -- a headwind even if price is holding up.
- Follow-through day: none in the recent window.

## 2. Leading Themes

Ranked by breadth of strength (share of each sector's names with an RS score >= 70), not raw average price change -- see Risk & Process Notes.

| Sector | Names Scanned | Median RS | % RS >= 70 | Clearing a Screen |
|---|---|---|---|---|
| Energy | 21 | 87 | 71% | 14 |
| Information Technology | 90 | 74 | 57% | 24 |
| Health Care | 60 | 72 | 57% | 27 |
| Materials | 26 | 58 | 31% | 4 |
| Industrials | 79 | 43 | 23% | 12 |
| Consumer Staples | 31 | 46 | 19% | 6 |
| Consumer Discretionary | 53 | 31 | 19% | 5 |
| Financials | 70 | 46 | 16% | 8 |
| Communication Services | 20 | 34 | 5% | 1 |
| Real Estate | 29 | 36 | 3% | 2 |
| Utilities | 31 | 32 | 0% | 1 |
| Unknown | 3 | 5 | 0% | 0 |

**Leading theme: Energy** — 71% of its 21 scanned names carry an RS score of 70+, and 14 name(s) are clearing a screen outright today.

## 3. Leading Stocks

**Leader spotlight** — the strongest names driving today's leading themes:

- **MRNA** (Health Care) — RS 99.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MRVL** (Information Technology) — RS 98.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRVL)
- **CRWD** (Information Technology) — RS 98.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=CRWD)

**Energy** (14)

### MPC — Energy [chart](https://www.tradingview.com/chart/?symbol=MPC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 484.92
- Entry: pivot 484.92 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.17x
- ADR%: 3.8% | RS score: 97.0
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
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### PSX — Energy [chart](https://www.tradingview.com/chart/?symbol=PSX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 297.29
- Entry: pivot 297.29 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.05x
- ADR%: 3.3% | RS score: 96.0
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
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### APA — Energy [chart](https://www.tradingview.com/chart/?symbol=APA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.9
- Entry: pivot 51.9 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 3.2% | RS score: 96.0
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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### TRGP — Energy [chart](https://www.tradingview.com/chart/?symbol=TRGP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 304.68
- Entry: pivot 304.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.96x
- ADR%: 2.6% | RS score: 94.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### COP — Energy [chart](https://www.tradingview.com/chart/?symbol=COP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 151.37
- Entry: pivot 151.37 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.88x
- ADR%: 2.3% | RS score: 93.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EOG — Energy [chart](https://www.tradingview.com/chart/?symbol=EOG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 163.68
- Entry: pivot 163.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 2.3% | RS score: 90.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CVX — Energy [chart](https://www.tradingview.com/chart/?symbol=CVX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 233.21
- Entry: pivot 233.21 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.76x
- ADR%: 1.9% | RS score: 90.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### XOM — Energy [chart](https://www.tradingview.com/chart/?symbol=XOM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 184.54
- Entry: pivot 184.54 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.07x
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

### OXY — Energy [chart](https://www.tradingview.com/chart/?symbol=OXY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 64.17
- Entry: pivot 64.17 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
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

### DVN — Energy [chart](https://www.tradingview.com/chart/?symbol=DVN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.64
- Entry: pivot 51.64 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
- ADR%: 2.8% | RS score: 87.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### OKE — Energy [chart](https://www.tradingview.com/chart/?symbol=OKE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 96.36
- Entry: pivot 96.36 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 2.4% | RS score: 83.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### FANG — Energy [chart](https://www.tradingview.com/chart/?symbol=FANG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 207.13
- Entry: pivot 207.13 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.54x
- ADR%: 2.4% | RS score: 77.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SLB — Energy [chart](https://www.tradingview.com/chart/?symbol=SLB)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.92x avg, needs 1.5x)
- Pivot (breakout trigger level): 53.08
- Entry: next session's open, only if volume confirms (price is already above pivot 53.08 on light volume)
- Volume vs 50-day avg: 0.92x
- ADR%: 3.0% | RS score: 76.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### KMI — Energy [chart](https://www.tradingview.com/chart/?symbol=KMI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 34.43
- Entry: pivot 34.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.14x
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
  - Riding the trend: yes, above 10/20-EMA

</details>

**Information Technology** (23)

### MRVL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MRVL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 286.95
- Entry: pivot 286.95 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.72x
- ADR%: 5.8% | RS score: 98.0
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
  - ADR%: 5.8% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CRWD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 278.86
- Entry: pivot 278.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.7x
- ADR%: 4.5% | RS score: 98.0
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
  - ADR%: 4.5% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HPE — Information Technology [chart](https://www.tradingview.com/chart/?symbol=HPE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 73.46
- Entry: pivot 73.46 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.53x
- ADR%: 4.9% | RS score: 98.0
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
  - ADR%: 4.9% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AMD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AMD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 649.42
- Entry: pivot 649.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.03x
- ADR%: 3.9% | RS score: 97.0
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
  - ADR%: 3.9% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FTNT — Information Technology [chart](https://www.tradingview.com/chart/?symbol=FTNT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 194.75
- Entry: pivot 194.75 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.89x
- ADR%: 3.4% | RS score: 97.0
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
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PANW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PANW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 419.91
- Entry: pivot 419.91 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
- ADR%: 4.2% | RS score: 97.0
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
  - ADR%: 4.2% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### NTAP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 239.18
- Entry: pivot 239.18 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.5x
- ADR%: 3.8% | RS score: 97.0
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
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DDOG — Information Technology [chart](https://www.tradingview.com/chart/?symbol=DDOG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 293.26
- Entry: pivot 293.26 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.84x
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

### FFIV — Information Technology [chart](https://www.tradingview.com/chart/?symbol=FFIV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 479.83
- Entry: pivot 479.83 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 2.96x
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

### ZBRA — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ZBRA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 391.0
- Entry: pivot 391.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.18x
- ADR%: 2.5% | RS score: 94.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HPQ — Information Technology [chart](https://www.tradingview.com/chart/?symbol=HPQ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 34.09
- Entry: pivot 34.09 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
- ADR%: 3.7% | RS score: 94.0
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
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PLTR — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PLTR)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 209.05
- Entry: pivot 209.05 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
- ADR%: 4.0% | RS score: 93.0
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
  - ADR%: 4.0% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ADI — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ADI)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.17x avg, needs 1.5x)
- Pivot (breakout trigger level): 420.55
- Entry: next session's open, only if volume confirms (price is already above pivot 420.55 on light volume)
- Volume vs 50-day avg: 1.17x
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
  - Riding the trend: yes, above 10/20-EMA

</details>

### SWKS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=SWKS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 88.04
- Entry: pivot 88.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.39x
- ADR%: 4.3% | RS score: 92.0
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
  - ADR%: 4.3% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CSCO — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CSCO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 118.39
- Entry: pivot 118.39 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.86x
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
  - Riding the trend: yes, above 10/20-EMA

</details>

### MSFT — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MSFT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 543.45
- Entry: pivot 543.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 1.9% | RS score: 85.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SHOP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=SHOP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 179.22
- Entry: pivot 179.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 4.1% | RS score: 84.0
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
  - ADR%: 4.1% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### AAPL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AAPL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 348.22
- Entry: pivot 348.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.98x
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

### ADP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ADP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 307.94
- Entry: pivot 307.94 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.02x
- ADR%: 2.0% | RS score: 79.0
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
  - RS score used: 79.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CDW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CDW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 165.11
- Entry: pivot 165.11 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 3.4% | RS score: 74.0
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
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### GRMN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=GRMN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 295.4
- Entry: pivot 295.4 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.14x
- ADR%: 2.6% | RS score: 73.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VRSN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=VRSN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 308.72
- Entry: pivot 308.72 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.91x
- ADR%: 2.7% | RS score: 71.0
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
  - RS score used: 71.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MSI — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MSI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 485.62
- Entry: pivot 485.62 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
- ADR%: 1.6% | RS score: 71.0
- Stage: Stage 3 (Topping)
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
  - RS score used: 71.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Health Care** (25)

### MRNA — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 245.81
- Entry: pivot 245.81 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 10.3% | RS score: 99.0
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
  - ADR%: 10.3% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CRL — Health Care [chart](https://www.tradingview.com/chart/?symbol=CRL)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.14x avg, needs 1.5x)
- Pivot (breakout trigger level): 357.27
- Entry: next session's open, only if volume confirms (price is already above pivot 357.27 on light volume)
- Volume vs 50-day avg: 1.14x
- ADR%: 4.2% | RS score: 96.0
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
  - ADR%: 4.2% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CNC — Health Care [chart](https://www.tradingview.com/chart/?symbol=CNC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 71.24
- Entry: pivot 71.24 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 2.59x
- ADR%: 3.6% | RS score: 95.0
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
  - ADR%: 3.6% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VEEV — Health Care [chart](https://www.tradingview.com/chart/?symbol=VEEV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 323.04
- Entry: pivot 323.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.82x
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

### RVTY — Health Care [chart](https://www.tradingview.com/chart/?symbol=RVTY)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.81x avg, needs 1.5x)
- Pivot (breakout trigger level): 160.39
- Entry: next session's open, only if volume confirms (price is already above pivot 160.39 on light volume)
- Volume vs 50-day avg: 0.81x
- ADR%: 3.9% | RS score: 95.0
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
  - ADR%: 3.9% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HUM — Health Care [chart](https://www.tradingview.com/chart/?symbol=HUM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 433.5
- Entry: pivot 433.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.54x
- ADR%: 3.7% | RS score: 95.0
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
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### BIIB — Health Care [chart](https://www.tradingview.com/chart/?symbol=BIIB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 253.84
- Entry: pivot 253.84 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.32x
- ADR%: 2.7% | RS score: 93.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VTRS — Health Care [chart](https://www.tradingview.com/chart/?symbol=VTRS)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.72x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 18.66
- Entry: next session's open, only if volume confirms (price is already above pivot 18.66 on light volume)
- Volume vs 50-day avg: 0.72x
- ADR%: 2.6% | RS score: 92.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### WST — Health Care [chart](https://www.tradingview.com/chart/?symbol=WST)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.44x avg, needs 1.5x)
- Pivot (breakout trigger level): 394.73
- Entry: next session's open, only if volume confirms (price is already above pivot 394.73 on light volume)
- Volume vs 50-day avg: 1.44x
- ADR%: 2.2% | RS score: 91.0
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
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### A — Health Care [chart](https://www.tradingview.com/chart/?symbol=A)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 177.75
- Entry: pivot 177.75 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.94x
- ADR%: 2.8% | RS score: 91.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WAT — Health Care [chart](https://www.tradingview.com/chart/?symbol=WAT)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.02x avg, needs 1.5x)
- Pivot (breakout trigger level): 457.47
- Entry: next session's open, only if volume confirms (price is already above pivot 457.47 on light volume)
- Volume vs 50-day avg: 1.02x
- ADR%: 3.2% | RS score: 90.0
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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AMGN — Health Care [chart](https://www.tradingview.com/chart/?symbol=AMGN)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.62x avg, needs 1.5x)
- Pivot (breakout trigger level): 447.28
- Entry: next session's open, only if volume confirms (price is already above pivot 447.28 on light volume)
- Volume vs 50-day avg: 0.62x
- ADR%: 2.3% | RS score: 90.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### LLY — Health Care [chart](https://www.tradingview.com/chart/?symbol=LLY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1306.69
- Entry: pivot 1306.69 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
- ADR%: 2.9% | RS score: 88.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### IQV — Health Care [chart](https://www.tradingview.com/chart/?symbol=IQV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 279.36
- Entry: pivot 279.36 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.44x
- ADR%: 3.2% | RS score: 87.0
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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### BDX — Health Care [chart](https://www.tradingview.com/chart/?symbol=BDX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 200.42
- Entry: pivot 200.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 2.1% | RS score: 87.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### TMO — Health Care [chart](https://www.tradingview.com/chart/?symbol=TMO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 696.49
- Entry: pivot 696.49 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.82x
- ADR%: 3.1% | RS score: 86.0
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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ABBV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ABBV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 289.08
- Entry: pivot 289.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.7x
- ADR%: 2.3% | RS score: 86.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CAH — Health Care [chart](https://www.tradingview.com/chart/?symbol=CAH)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 257.55
- Entry: pivot 257.55 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.96x
- ADR%: 2.3% | RS score: 84.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ELV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ELV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 445.28
- Entry: pivot 445.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.27x
- ADR%: 2.9% | RS score: 82.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### DGX — Health Care [chart](https://www.tradingview.com/chart/?symbol=DGX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 243.28
- Entry: pivot 243.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
- ADR%: 2.4% | RS score: 82.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PFE — Health Care [chart](https://www.tradingview.com/chart/?symbol=PFE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 30.42
- Entry: pivot 30.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
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

### JNJ — Health Care [chart](https://www.tradingview.com/chart/?symbol=JNJ)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.83x avg, needs 1.5x)
- Pivot (breakout trigger level): 267.61
- Entry: next session's open, only if volume confirms (price is already above pivot 267.61 on light volume)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.1% | RS score: 79.0
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
  - RS score used: 79.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### LH — Health Care [chart](https://www.tradingview.com/chart/?symbol=LH)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.11x avg, needs 1.5x)
- Pivot (breakout trigger level): 329.93
- Entry: next session's open, only if volume confirms (price is already above pivot 329.93 on light volume)
- Volume vs 50-day avg: 1.11x
- ADR%: 2.1% | RS score: 78.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### BAX — Health Care [chart](https://www.tradingview.com/chart/?symbol=BAX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 25.76
- Entry: pivot 25.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
- ADR%: 2.8% | RS score: 74.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### UNH — Health Care [chart](https://www.tradingview.com/chart/?symbol=UNH)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 424.98
- Entry: pivot 424.98 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.9% | RS score: 73.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Materials** (3)

### NUE — Materials [chart](https://www.tradingview.com/chart/?symbol=NUE)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 264.54
- Entry: next session's open (pivot 264.54 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.78x
- ADR%: 2.9% | RS score: 93.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 1.78x the 50-day average (needs >= 1.5x)

</details>

### IFF — Materials [chart](https://www.tradingview.com/chart/?symbol=IFF)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 94.15
- Entry: pivot 94.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.55x
- ADR%: 2.0% | RS score: 88.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### STLD — Materials [chart](https://www.tradingview.com/chart/?symbol=STLD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 247.97
- Entry: pivot 247.97 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.09x
- ADR%: 3.3% | RS score: 85.0
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
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Industrials** (12)

### EXPD — Industrials [chart](https://www.tradingview.com/chart/?symbol=EXPD)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.85x avg, needs 1.5x)
- Pivot (breakout trigger level): 198.64
- Entry: next session's open, only if volume confirms (price is already above pivot 198.64 on light volume)
- Volume vs 50-day avg: 0.85x
- ADR%: 2.0% | RS score: 91.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SWK — Industrials [chart](https://www.tradingview.com/chart/?symbol=SWK)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 99.37
- Entry: pivot 99.37 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 2.7% | RS score: 86.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CSX — Industrials [chart](https://www.tradingview.com/chart/?symbol=CSX)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.98x avg, needs 1.5x)
- Pivot (breakout trigger level): 51.67
- Entry: next session's open, only if volume confirms (price is already above pivot 51.67 on light volume)
- Volume vs 50-day avg: 0.98x
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

</details>

### JCI — Industrials [chart](https://www.tradingview.com/chart/?symbol=JCI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 158.76
- Entry: pivot 158.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.81x
- ADR%: 2.7% | RS score: 84.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### URI — Industrials [chart](https://www.tradingview.com/chart/?symbol=URI)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.18x avg, needs 1.5x)
- Pivot (breakout trigger level): 1121.9
- Entry: next session's open, only if volume confirms (price is already above pivot 1121.9 on light volume)
- Volume vs 50-day avg: 1.18x
- ADR%: 3.5% | RS score: 81.0
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
  - ADR%: 3.5% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EMR — Industrials [chart](https://www.tradingview.com/chart/?symbol=EMR)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.94x avg, needs 1.5x)
- Pivot (breakout trigger level): 163.5
- Entry: next session's open, only if volume confirms (price is already above pivot 163.5 on light volume)
- Volume vs 50-day avg: 0.94x
- ADR%: 2.6% | RS score: 80.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### NDSN — Industrials [chart](https://www.tradingview.com/chart/?symbol=NDSN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 334.43
- Entry: pivot 334.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
- ADR%: 2.0% | RS score: 80.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### UNP — Industrials [chart](https://www.tradingview.com/chart/?symbol=UNP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.68x avg, needs 1.5x)
- Pivot (breakout trigger level): 298.09
- Entry: next session's open, only if volume confirms (price is already above pivot 298.09 on light volume)
- Volume vs 50-day avg: 0.68x
- ADR%: 1.8% | RS score: 80.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### GWW — Industrials [chart](https://www.tradingview.com/chart/?symbol=GWW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1360.08
- Entry: pivot 1360.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 2.1% | RS score: 76.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### IEX — Industrials [chart](https://www.tradingview.com/chart/?symbol=IEX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 238.62
- Entry: pivot 238.62 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.57x
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

### FAST — Industrials [chart](https://www.tradingview.com/chart/?symbol=FAST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 52.73
- Entry: pivot 52.73 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.6% | RS score: 73.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DAL — Industrials [chart](https://www.tradingview.com/chart/?symbol=DAL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 84.63
- Entry: pivot 84.63 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.0x
- ADR%: 3.4% | RS score: 72.0
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
  - RS score used: 72.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Consumer Staples** (5)

### KDP — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KDP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 35.19
- Entry: pivot 35.19 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
- ADR%: 2.4% | RS score: 84.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SJM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=SJM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 133.39
- Entry: pivot 133.39 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.52x
- ADR%: 2.2% | RS score: 79.0
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
  - RS score used: 79.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### KO — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 95.34
- Entry: pivot 95.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.1x
- ADR%: 1.6% | RS score: 77.0
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
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=PM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 205.58
- Entry: pivot 205.58 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
- ADR%: 2.5% | RS score: 75.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### KVUE — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KVUE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 19.88
- Entry: pivot 19.88 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.7x
- ADR%: 1.7% | RS score: 71.0
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
  - RS score used: 71.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Consumer Discretionary** (3)

### BBY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=BBY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 99.87
- Entry: pivot 99.87 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 3.1% | RS score: 91.0
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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WSM — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=WSM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 260.8
- Entry: pivot 260.8 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 2.7% | RS score: 84.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EBAY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=EBAY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 122.91
- Entry: pivot 122.91 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
- ADR%: 2.8% | RS score: 72.0
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
  - RS score used: 72.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Financials** (7)

### TRV — Financials [chart](https://www.tradingview.com/chart/?symbol=TRV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 405.44
- Entry: pivot 405.44 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 1.9% | RS score: 87.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MET — Financials [chart](https://www.tradingview.com/chart/?symbol=MET)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 103.57
- Entry: pivot 103.57 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.62x
- ADR%: 2.0% | RS score: 82.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### V — Financials [chart](https://www.tradingview.com/chart/?symbol=V)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 414.34
- Entry: pivot 414.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.34x
- ADR%: 1.7% | RS score: 79.0
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
  - RS score used: 79.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AIZ — Financials [chart](https://www.tradingview.com/chart/?symbol=AIZ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 288.85
- Entry: pivot 288.85 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
- ADR%: 1.7% | RS score: 78.0
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
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### FDS — Financials [chart](https://www.tradingview.com/chart/?symbol=FDS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 335.45
- Entry: pivot 335.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.99x
- ADR%: 3.7% | RS score: 77.0
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
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PFG — Financials [chart](https://www.tradingview.com/chart/?symbol=PFG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 113.97
- Entry: pivot 113.97 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 2.27x
- ADR%: 2.1% | RS score: 76.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ALL — Financials [chart](https://www.tradingview.com/chart/?symbol=ALL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 259.1
- Entry: pivot 259.1 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.67x
- ADR%: 2.0% | RS score: 70.0
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
  - RS score used: 70.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Real Estate** (1)

### HST — Real Estate [chart](https://www.tradingview.com/chart/?symbol=HST)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.0x avg, needs 1.5x)
- Pivot (breakout trigger level): 25.09
- Entry: next session's open, only if volume confirms (price is already above pivot 25.09 on light volume)
- Volume vs 50-day avg: 1.0x
- ADR%: 2.1% | RS score: 88.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>


## 4. Worth Watching

Market regime reads **defensive**, and **Energy** is leading with 71% of its names carrying RS 70+ and 14 clearing a screen outright today. On that basis, these 8 name(s) are worth watching:

- **MRNA** (Health Care) — VCP contraction (watch for trigger), RS 99.0, pivot 245.81. Entry: pivot 245.81 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MRVL** (Information Technology) — VCP contraction (watch for trigger), RS 98.0, pivot 286.95. Entry: pivot 286.95 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MRVL)
- **CRWD** (Information Technology) — VCP contraction (watch for trigger), RS 98.0, pivot 278.86. Entry: pivot 278.86 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- **HPE** (Information Technology) — VCP contraction (watch for trigger), RS 98.0, pivot 73.46. Entry: pivot 73.46 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=HPE)
- **MPC** (Energy) — VCP contraction (watch for trigger), RS 97.0, pivot 484.92. Entry: pivot 484.92 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MPC)
- **AMD** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 649.42. Entry: pivot 649.42 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=AMD)
- **FTNT** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 194.75. Entry: pivot 194.75 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=FTNT)
- **PANW** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 419.91. Entry: pivot 419.91 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=PANW)

## 5. Other Setups (context)

No Episodic Pivots or notably extended/parabolic names flagged today.

## 6. Names to Avoid / Under Distribution

No prior leaders showing a clear technical breakdown flagged today.

## 7. Risk & Process Notes
- Universe scanned: 520 tickers.
- Minervini stop discipline: ~7-8% max below entry, sized to keep account risk small.
- Qullamaggie stop discipline: stop within ~1x ADR of entry; risk ~0.25-1% of account per trade.
- VCP/staging flags are rule-based approximations of a visual pattern — confirm on the linked TradingView chart.
- Leading Themes is ranked by breadth of RS strength, not raw average price change, so it isn't skewed by one outlier name in an otherwise quiet sector.
- Breadth, distribution-day, and follow-through-day stats are simplified approximations of IBD's own methodology, computed from the same price history already pulled for this run — directional signal, not an exact replica.
- A "Defensive" Market Pulse read doesn't rule a setup out: in the backtest, skipping those entries cut the return.

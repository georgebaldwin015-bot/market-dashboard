# Edge Lab — Daily Report (2026-10-28)
*Educational/informational output modeling Mark Minervini's and Kristjan "Qullamaggie" Kullamägi's publicly
described methodologies. Not personalized financial advice; this is not a licensed advisor. Confirm every
setup on an actual chart before acting.*
*Data source: Yahoo Finance (via yfinance), end-of-day bars. Universe defined in `universe.csv` — edit that file to expand coverage. Sector/industry groupings are derived live from Yahoo Finance and shared with the Daily Market Report tab via `industry_map.py`.*
## What's Going On

The market is in a defensive posture, with breadth reading 59% of the scanned universe above its 50-day moving average and 7 distribution days in the past month -- an elevated count worth watching. Zooming out, breadth has been deteriorating over the last 60 sessions (-5.5 pt change in % above the 50-day MA) and improving over the last two weeks (+20.5 pt), while SPY is roughly flat (+1.3% over 60 sessions, -1.6% over the last two weeks). Breadth actually improving while SPY chops or pulls back is a healthier under-the-surface signal than the index alone suggests. Momentum under the surface is leaning long -- 18 name(s) hit a fresh 52-week high today against 12 breaking down to a fresh 52-week low. Energy is leading, with 71% of its 21 scanned names carrying an RS score of 70+ and 15 clearing a screen outright today, with Health Care also showing real strength. It's being driven by names like MPC, APA and PSX. With 92 name(s) clearing a screen across 10 sector(s), there's a workable watchlist below -- see Worth Watching for the shortlist tied to today's regime and themes.

## 1. Market Pulse

Market cycle: **Bull** -- equal-weight universe index +6.0% vs its 200-day MA, 50-day MA +4.9% vs the 200-day. Trade normally.

SPY close: 765.37 | 10-day MA: 768.06 | 20-day MA: 770.14

**Defensive** — 10-day MA below the 20-day. Setups that still pass the rules here averaged a little less (+0.5R vs +0.7R a trade) but skipping them cut the backtest's return: trade the plan.

- Breadth: 59% of the scanned universe above its 50-day MA, 60% above its 200-day MA.
- 52-week breakouts vs breakdowns today: 18 breakouts / 12 breakdowns (out of 519 names evaluated).
- Distribution days (SPY, trailing 25 sessions): 7. Elevated -- a headwind even if price is holding up.
- Follow-through day: none in the recent window.

## 2. Leading Themes

Ranked by breadth of strength (share of each sector's names with an RS score >= 70), not raw average price change -- see Risk & Process Notes.

| Sector | Names Scanned | Median RS | % RS >= 70 | Clearing a Screen |
|---|---|---|---|---|
| Energy | 21 | 90 | 71% | 15 |
| Health Care | 60 | 74 | 55% | 25 |
| Information Technology | 90 | 72 | 52% | 21 |
| Materials | 26 | 58 | 27% | 5 |
| Consumer Staples | 31 | 53 | 26% | 8 |
| Industrials | 79 | 37 | 22% | 11 |
| Financials | 70 | 48 | 20% | 7 |
| Consumer Discretionary | 53 | 29 | 19% | 5 |
| Communication Services | 20 | 36 | 10% | 3 |
| Real Estate | 29 | 38 | 7% | 2 |
| Utilities | 31 | 33 | 0% | 0 |
| Unknown | 3 | 6 | 0% | 0 |

**Leading theme: Energy** — 71% of its 21 scanned names carry an RS score of 70+, and 15 name(s) are clearing a screen outright today.

## 3. Leading Stocks

**Leader spotlight** — the strongest names driving today's leading themes:

- **MRNA** (Health Care) — RS 99.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MPC** (Energy) — RS 98.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MPC)
- **APA** (Energy) — RS 97.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=APA)

**Energy** (15)

### MPC — Energy [chart](https://www.tradingview.com/chart/?symbol=MPC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 484.92
- Entry: pivot 484.92 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.58x
- ADR%: 3.6% | RS score: 98.0
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
  - ADR%: 3.6% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### APA — Energy [chart](https://www.tradingview.com/chart/?symbol=APA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.9
- Entry: pivot 51.9 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.21x
- ADR%: 3.2% | RS score: 97.0
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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PSX — Energy [chart](https://www.tradingview.com/chart/?symbol=PSX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 297.29
- Entry: pivot 297.29 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
- ADR%: 3.1% | RS score: 97.0
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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VLO — Energy [chart](https://www.tradingview.com/chart/?symbol=VLO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 459.78
- Entry: pivot 459.78 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
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

### COP — Energy [chart](https://www.tradingview.com/chart/?symbol=COP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.81x avg, needs 1.5x)
- Pivot (breakout trigger level): 150.8
- Entry: next session's open, only if volume confirms (price is already above pivot 150.8 on light volume)
- Volume vs 50-day avg: 0.81x
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

</details>

### TRGP — Energy [chart](https://www.tradingview.com/chart/?symbol=TRGP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.72x avg, needs 1.5x)
- Pivot (breakout trigger level): 302.37
- Entry: next session's open, only if volume confirms (price is already above pivot 302.37 on light volume)
- Volume vs 50-day avg: 0.72x
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

### CVX — Energy [chart](https://www.tradingview.com/chart/?symbol=CVX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 233.21
- Entry: pivot 233.21 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.82x
- ADR%: 1.9% | RS score: 93.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### XOM — Energy [chart](https://www.tradingview.com/chart/?symbol=XOM)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.82x avg, needs 1.5x)
- Pivot (breakout trigger level): 183.21
- Entry: next session's open, only if volume confirms (price is already above pivot 183.21 on light volume)
- Volume vs 50-day avg: 0.82x
- ADR%: 1.9% | RS score: 93.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EOG — Energy [chart](https://www.tradingview.com/chart/?symbol=EOG)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.68x avg, needs 1.5x)
- Pivot (breakout trigger level): 163.03
- Entry: next session's open, only if volume confirms (price is already above pivot 163.03 on light volume)
- Volume vs 50-day avg: 0.68x
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

### OXY — Energy [chart](https://www.tradingview.com/chart/?symbol=OXY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 64.17
- Entry: pivot 64.17 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.86x
- ADR%: 2.4% | RS score: 90.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DVN — Energy [chart](https://www.tradingview.com/chart/?symbol=DVN)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.77x avg, needs 1.5x)
- Pivot (breakout trigger level): 51.39
- Entry: next session's open, only if volume confirms (price is already above pivot 51.39 on light volume)
- Volume vs 50-day avg: 0.77x
- ADR%: 2.8% | RS score: 90.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### OKE — Energy [chart](https://www.tradingview.com/chart/?symbol=OKE)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.64x avg, needs 1.5x)
- Pivot (breakout trigger level): 95.83
- Entry: next session's open, only if volume confirms (price is already above pivot 95.83 on light volume)
- Volume vs 50-day avg: 0.64x
- ADR%: 2.5% | RS score: 83.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FANG — Energy [chart](https://www.tradingview.com/chart/?symbol=FANG)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.55x avg, needs 1.5x)
- Pivot (breakout trigger level): 205.75
- Entry: next session's open, only if volume confirms (price is already above pivot 205.75 on light volume)
- Volume vs 50-day avg: 0.55x
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

</details>

### KMI — Energy [chart](https://www.tradingview.com/chart/?symbol=KMI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 34.43
- Entry: pivot 34.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.68x
- ADR%: 2.6% | RS score: 76.0
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
  - RS score used: 76.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SLB — Energy [chart](https://www.tradingview.com/chart/?symbol=SLB)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.99x avg, needs 1.5x)
- Pivot (breakout trigger level): 53.06
- Entry: next session's open, only if volume confirms (price is already above pivot 53.06 on light volume)
- Volume vs 50-day avg: 0.99x
- ADR%: 2.9% | RS score: 72.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Health Care** (23)

### MRNA — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 245.81
- Entry: pivot 245.81 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
- ADR%: 10.0% | RS score: 99.0
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
  - ADR%: 10.0% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### CRL — Health Care [chart](https://www.tradingview.com/chart/?symbol=CRL)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.16x avg, needs 1.5x)
- Pivot (breakout trigger level): 345.37
- Entry: next session's open, only if volume confirms (price is already above pivot 345.37 on light volume)
- Volume vs 50-day avg: 1.16x
- ADR%: 4.3% | RS score: 96.0
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
  - ADR%: 4.3% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### RVTY — Health Care [chart](https://www.tradingview.com/chart/?symbol=RVTY)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.57x avg, needs 1.5x)
- Pivot (breakout trigger level): 158.77
- Entry: next session's open, only if volume confirms (price is already above pivot 158.77 on light volume)
- Volume vs 50-day avg: 0.57x
- ADR%: 3.8% | RS score: 96.0
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
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VEEV — Health Care [chart](https://www.tradingview.com/chart/?symbol=VEEV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 323.04
- Entry: pivot 323.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
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

### CNC — Health Care [chart](https://www.tradingview.com/chart/?symbol=CNC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 71.24
- Entry: pivot 71.24 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.5x
- ADR%: 3.2% | RS score: 94.0
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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HUM — Health Care [chart](https://www.tradingview.com/chart/?symbol=HUM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 433.5
- Entry: pivot 433.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.01x
- ADR%: 3.8% | RS score: 94.0
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
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### BIIB — Health Care [chart](https://www.tradingview.com/chart/?symbol=BIIB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 253.84
- Entry: pivot 253.84 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
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

### WST — Health Care [chart](https://www.tradingview.com/chart/?symbol=WST)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.21x avg, needs 1.5x)
- Pivot (breakout trigger level): 394.03
- Entry: next session's open, only if volume confirms (price is already above pivot 394.03 on light volume)
- Volume vs 50-day avg: 1.21x
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

### VTRS — Health Care [chart](https://www.tradingview.com/chart/?symbol=VTRS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 18.66
- Entry: pivot 18.66 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.72x
- ADR%: 2.5% | RS score: 91.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### A — Health Care [chart](https://www.tradingview.com/chart/?symbol=A)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 177.75
- Entry: pivot 177.75 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.7% | RS score: 91.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### AMGN — Health Care [chart](https://www.tradingview.com/chart/?symbol=AMGN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 447.28
- Entry: pivot 447.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
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
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### WAT — Health Care [chart](https://www.tradingview.com/chart/?symbol=WAT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 457.47
- Entry: pivot 457.47 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.17x
- ADR%: 3.1% | RS score: 88.0
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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 88.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### LLY — Health Care [chart](https://www.tradingview.com/chart/?symbol=LLY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1306.69
- Entry: pivot 1306.69 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.89x
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
- Volume vs 50-day avg: 1.17x
- ADR%: 3.0% | RS score: 87.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ABBV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ABBV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 289.08
- Entry: pivot 289.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.97x
- ADR%: 2.3% | RS score: 87.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CAH — Health Care [chart](https://www.tradingview.com/chart/?symbol=CAH)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 257.55
- Entry: pivot 257.55 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.99x
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

### TMO — Health Care [chart](https://www.tradingview.com/chart/?symbol=TMO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 696.49
- Entry: pivot 696.49 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.88x
- ADR%: 3.0% | RS score: 85.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DGX — Health Care [chart](https://www.tradingview.com/chart/?symbol=DGX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 243.28
- Entry: pivot 243.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.91x
- ADR%: 2.5% | RS score: 82.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PFE — Health Care [chart](https://www.tradingview.com/chart/?symbol=PFE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 30.42
- Entry: pivot 30.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
- ADR%: 1.9% | RS score: 81.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ELV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ELV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 445.28
- Entry: pivot 445.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.2x
- ADR%: 2.7% | RS score: 79.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### JNJ — Health Care [chart](https://www.tradingview.com/chart/?symbol=JNJ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 271.95
- Entry: pivot 271.95 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.2% | RS score: 77.0
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
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### BAX — Health Care [chart](https://www.tradingview.com/chart/?symbol=BAX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 25.76
- Entry: pivot 25.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
- ADR%: 2.8% | RS score: 77.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### LH — Health Care [chart](https://www.tradingview.com/chart/?symbol=LH)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 329.93
- Entry: pivot 329.93 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.91x
- ADR%: 2.0% | RS score: 75.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Information Technology** (19)

### NTAP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 239.18
- Entry: pivot 239.18 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.97x
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

### CRWD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 278.86
- Entry: pivot 278.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.81x
- ADR%: 4.5% | RS score: 97.0
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
  - ADR%: 4.5% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FTNT — Information Technology [chart](https://www.tradingview.com/chart/?symbol=FTNT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 194.75
- Entry: pivot 194.75 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
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
- Volume vs 50-day avg: 0.85x
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

### DDOG — Information Technology [chart](https://www.tradingview.com/chart/?symbol=DDOG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 293.26
- Entry: pivot 293.26 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 4.8% | RS score: 96.0
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
  - ADR%: 4.8% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ZBRA — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ZBRA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 391.0
- Entry: pivot 391.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.91x
- ADR%: 2.6% | RS score: 95.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HPQ — Information Technology [chart](https://www.tradingview.com/chart/?symbol=HPQ)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.79x avg, needs 1.5x)
- Pivot (breakout trigger level): 33.76
- Entry: next session's open, only if volume confirms (price is already above pivot 33.76 on light volume)
- Volume vs 50-day avg: 0.79x
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

### FFIV — Information Technology [chart](https://www.tradingview.com/chart/?symbol=FFIV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 479.83
- Entry: pivot 479.83 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.06x
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

### PLTR — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PLTR)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 209.05
- Entry: pivot 209.05 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 3.9% | RS score: 93.0
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
  - ADR%: 3.9% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SWKS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=SWKS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 88.04
- Entry: pivot 88.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.39x
- ADR%: 4.4% | RS score: 90.0
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
  - ADR%: 4.4% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### ADI — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ADI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 420.55
- Entry: pivot 420.55 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.09x
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

### CSCO — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CSCO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 118.39
- Entry: pivot 118.39 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.23x
- ADR%: 2.5% | RS score: 86.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MSFT — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MSFT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 543.45
- Entry: pivot 543.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
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

### ADP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ADP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 307.94
- Entry: pivot 307.94 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.22x
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

### GRMN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=GRMN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 295.4
- Entry: pivot 295.4 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
- ADR%: 2.6% | RS score: 84.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### AAPL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AAPL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 348.22
- Entry: pivot 348.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.05x
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

### CDW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CDW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 165.11
- Entry: pivot 165.11 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.95x
- ADR%: 3.4% | RS score: 78.0
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
  - ADR%: 3.4% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### VRSN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=VRSN)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.45x avg, needs 1.5x)
- Pivot (breakout trigger level): 307.25
- Entry: next session's open, only if volume confirms (price is already above pivot 307.25 on light volume)
- Volume vs 50-day avg: 1.45x
- ADR%: 2.6% | RS score: 77.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MSI — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MSI)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.04x avg, needs 1.5x)
- Pivot (breakout trigger level): 481.83
- Entry: next session's open, only if volume confirms (price is already above pivot 481.83 on light volume)
- Volume vs 50-day avg: 1.04x
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

**Materials** (4)

### NUE — Materials [chart](https://www.tradingview.com/chart/?symbol=NUE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 264.54
- Entry: pivot 264.54 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.21x
- ADR%: 2.9% | RS score: 90.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### IFF — Materials [chart](https://www.tradingview.com/chart/?symbol=IFF)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 94.15
- Entry: pivot 94.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.04x
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

### DOW — Materials [chart](https://www.tradingview.com/chart/?symbol=DOW)
- Screens passed: B (Momentum)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 32.61
- Entry: next session's open (pivot 32.61 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.61x
- ADR%: 3.1% | RS score: 81.0
- Stage: Stage 3 (Topping)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 81.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 1.61x the 50-day average (needs >= 1.5x)

</details>

### STLD — Materials [chart](https://www.tradingview.com/chart/?symbol=STLD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 247.97
- Entry: pivot 247.97 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.38x
- ADR%: 3.3% | RS score: 78.0
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
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

**Consumer Staples** (7)

### SJM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=SJM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 133.39
- Entry: pivot 133.39 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.04x
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

### KDP — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KDP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 35.19
- Entry: pivot 35.19 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.98x
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

### KO — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 95.34
- Entry: pivot 95.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.29x
- ADR%: 1.5% | RS score: 82.0
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
  - ADR%: 1.5% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=PM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 205.58
- Entry: pivot 205.58 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.11x
- ADR%: 2.5% | RS score: 76.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CCEP — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=CCEP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 114.23
- Entry: pivot 114.23 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 1.8% | RS score: 73.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### KVUE — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KVUE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 19.88
- Entry: pivot 19.88 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.42x
- ADR%: 1.7% | RS score: 72.0
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
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CHD — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=CHD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 108.86
- Entry: pivot 108.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.03x
- ADR%: 1.8% | RS score: 70.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Industrials** (10)

### EXPD — Industrials [chart](https://www.tradingview.com/chart/?symbol=EXPD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 198.64
- Entry: pivot 198.64 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.99x
- ADR%: 1.9% | RS score: 91.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SWK — Industrials [chart](https://www.tradingview.com/chart/?symbol=SWK)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.9x avg, needs 1.5x)
- Pivot (breakout trigger level): 99.24
- Entry: next session's open, only if volume confirms (price is already above pivot 99.24 on light volume)
- Volume vs 50-day avg: 0.9x
- ADR%: 2.9% | RS score: 84.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CSX — Industrials [chart](https://www.tradingview.com/chart/?symbol=CSX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.67
- Entry: pivot 51.67 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.89x
- ADR%: 1.7% | RS score: 81.0
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
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### GWW — Industrials [chart](https://www.tradingview.com/chart/?symbol=GWW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1360.08
- Entry: pivot 1360.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
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

### UNP — Industrials [chart](https://www.tradingview.com/chart/?symbol=UNP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 298.09
- Entry: pivot 298.09 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 1.8% | RS score: 76.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FAST — Industrials [chart](https://www.tradingview.com/chart/?symbol=FAST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 52.73
- Entry: pivot 52.73 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.7x
- ADR%: 2.6% | RS score: 76.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### JCI — Industrials [chart](https://www.tradingview.com/chart/?symbol=JCI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 158.76
- Entry: pivot 158.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.24x
- ADR%: 2.6% | RS score: 75.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### IEX — Industrials [chart](https://www.tradingview.com/chart/?symbol=IEX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 238.62
- Entry: pivot 238.62 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.06x
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
  - Riding the trend: no

</details>

### URI — Industrials [chart](https://www.tradingview.com/chart/?symbol=URI)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.89x avg, needs 1.5x)
- Pivot (breakout trigger level): 1111.02
- Entry: next session's open, only if volume confirms (price is already above pivot 1111.02 on light volume)
- Volume vs 50-day avg: 0.89x
- ADR%: 3.7% | RS score: 73.0
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
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EMR — Industrials [chart](https://www.tradingview.com/chart/?symbol=EMR)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 163.5
- Entry: pivot 163.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.2x
- ADR%: 2.6% | RS score: 70.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Financials** (7)

### TRV — Financials [chart](https://www.tradingview.com/chart/?symbol=TRV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 405.44
- Entry: pivot 405.44 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
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
- Volume vs 50-day avg: 0.98x
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

### FDS — Financials [chart](https://www.tradingview.com/chart/?symbol=FDS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 335.45
- Entry: pivot 335.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
- ADR%: 3.8% | RS score: 82.0
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
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### V — Financials [chart](https://www.tradingview.com/chart/?symbol=V)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 414.34
- Entry: pivot 414.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.84x
- ADR%: 1.7% | RS score: 80.0
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
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AIZ — Financials [chart](https://www.tradingview.com/chart/?symbol=AIZ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 288.85
- Entry: pivot 288.85 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.51x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### ALL — Financials [chart](https://www.tradingview.com/chart/?symbol=ALL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 259.1
- Entry: pivot 259.1 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 1.9% | RS score: 74.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MA — Financials [chart](https://www.tradingview.com/chart/?symbol=MA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 633.21
- Entry: pivot 633.21 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.97x
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

**Consumer Discretionary** (4)

### BBY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=BBY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 99.87
- Entry: pivot 99.87 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.61x
- ADR%: 3.1% | RS score: 92.0
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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WSM — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=WSM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 260.8
- Entry: pivot 260.8 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 2.7% | RS score: 82.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EBAY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=EBAY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 122.91
- Entry: pivot 122.91 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.88x
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

### ROST — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=ROST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 238.66
- Entry: pivot 238.66 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 2.2% | RS score: 71.0
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
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Communication Services** (1)

### NWSA — Communication Services [chart](https://www.tradingview.com/chart/?symbol=NWSA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 31.08
- Entry: pivot 31.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.0% | RS score: 71.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Real Estate** (2)

### HST — Real Estate [chart](https://www.tradingview.com/chart/?symbol=HST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 25.09
- Entry: pivot 25.09 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.91x
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

### WELL — Real Estate [chart](https://www.tradingview.com/chart/?symbol=WELL)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.9x avg, needs 1.5x)
- Pivot (breakout trigger level): 238.08
- Entry: next session's open, only if volume confirms (price is already above pivot 238.08 on light volume)
- Volume vs 50-day avg: 0.9x
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


## 4. Worth Watching

Market regime reads **defensive**, and **Energy** is leading with 71% of its names carrying RS 70+ and 15 clearing a screen outright today. On that basis, these 8 name(s) are worth watching:

- **MRNA** (Health Care) — VCP contraction (watch for trigger), RS 99.0, pivot 245.81. Entry: pivot 245.81 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MPC** (Energy) — VCP contraction (watch for trigger), RS 98.0, pivot 484.92. Entry: pivot 484.92 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MPC)
- **APA** (Energy) — VCP contraction (watch for trigger), RS 97.0, pivot 51.9. Entry: pivot 51.9 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=APA)
- **NTAP** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 239.18. Entry: pivot 239.18 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- **CRWD** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 278.86. Entry: pivot 278.86 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- **FTNT** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 194.75. Entry: pivot 194.75 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=FTNT)
- **PSX** (Energy) — VCP contraction (watch for trigger), RS 97.0, pivot 297.29. Entry: pivot 297.29 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=PSX)
- **VLO** (Energy) — VCP contraction (watch for trigger), RS 97.0, pivot 459.78. Entry: pivot 459.78 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=VLO)

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

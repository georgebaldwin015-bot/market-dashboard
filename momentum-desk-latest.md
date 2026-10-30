# Edge Lab — Daily Report (2026-10-30)
*Educational/informational output modeling Mark Minervini's and Kristjan "Qullamaggie" Kullamägi's publicly
described methodologies. Not personalized financial advice; this is not a licensed advisor. Confirm every
setup on an actual chart before acting.*
*Data source: Yahoo Finance (via yfinance), end-of-day bars. Universe defined in `universe.csv` — edit that file to expand coverage. Sector/industry groupings are derived live from Yahoo Finance and shared with the Daily Market Report tab via `industry_map.py`.*
## What's Going On

The market is in a defensive posture, with breadth reading 65% of the scanned universe above its 50-day moving average and 7 distribution days in the past month -- an elevated count worth watching. Zooming out, breadth has been roughly flat over the last 60 sessions (+0.3 pt change in % above the 50-day MA) and improving over the last two weeks (+20.1 pt), while SPY is roughly flat (+0.4% over 60 sessions, +0.8% over the last two weeks). Momentum under the surface is leaning firmly long -- 37 name(s) hit a fresh 52-week high today against 8 breaking down to a fresh 52-week low. Energy is leading, with 71% of its 21 scanned names carrying an RS score of 70+ and 14 clearing a screen outright today, with Health Care also showing real strength. It's being driven by names like MPC, APA and PSX. With 95 name(s) clearing a screen across 11 sector(s), there's a workable watchlist below -- see Worth Watching for the shortlist tied to today's regime and themes.

## 1. Market Pulse

Market cycle: **Bull** -- equal-weight universe index +7.3% vs its 200-day MA, 50-day MA +4.7% vs the 200-day. Trade normally.

SPY close: 769.36 | 10-day MA: 767.25 | 20-day MA: 771.16

**Defensive** — 10-day MA below the 20-day. Setups that still pass the rules here averaged a little less (+0.5R vs +0.7R a trade) but skipping them cut the backtest's return: trade the plan.

- Breadth: 65% of the scanned universe above its 50-day MA, 65% above its 200-day MA.
- 52-week breakouts vs breakdowns today: 37 breakouts / 8 breakdowns (out of 519 names evaluated).
- Distribution days (SPY, trailing 25 sessions): 7. Elevated -- a headwind even if price is holding up.
- Follow-through day: none in the recent window.

## 2. Leading Themes

Ranked by breadth of strength (share of each sector's names with an RS score >= 70), not raw average price change -- see Risk & Process Notes.

| Sector | Names Scanned | Median RS | % RS >= 70 | Clearing a Screen |
|---|---|---|---|---|
| Energy | 21 | 85 | 71% | 14 |
| Health Care | 60 | 74 | 53% | 32 |
| Information Technology | 90 | 72 | 51% | 17 |
| Materials | 26 | 62 | 35% | 6 |
| Consumer Staples | 31 | 48 | 26% | 7 |
| Industrials | 79 | 39 | 25% | 12 |
| Consumer Discretionary | 53 | 25 | 19% | 5 |
| Financials | 70 | 48 | 19% | 15 |
| Communication Services | 20 | 28 | 5% | 1 |
| Real Estate | 29 | 37 | 3% | 1 |
| Utilities | 31 | 36 | 0% | 2 |
| Unknown | 3 | 7 | 0% | 0 |

**Leading theme: Energy** — 71% of its 21 scanned names carry an RS score of 70+, and 14 name(s) are clearing a screen outright today.

## 3. Leading Stocks

**Leader spotlight** — the strongest names driving today's leading themes:

- **MRNA** (Health Care) — RS 99.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MPC** (Energy) — RS 98.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MPC)
- **CRWD** (Information Technology) — RS 98.0, VCP contraction (watch for trigger), Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=CRWD)

**Energy** (14)

### MPC — Energy [chart](https://www.tradingview.com/chart/?symbol=MPC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 484.92
- Entry: pivot 484.92 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.95x
- ADR%: 3.8% | RS score: 98.0
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
  - ADR%: 3.8% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### APA — Energy [chart](https://www.tradingview.com/chart/?symbol=APA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.9
- Entry: pivot 51.9 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.7x
- ADR%: 3.0% | RS score: 97.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PSX — Energy [chart](https://www.tradingview.com/chart/?symbol=PSX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 297.29
- Entry: pivot 297.29 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.12x
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

### TRGP — Energy [chart](https://www.tradingview.com/chart/?symbol=TRGP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.98x avg, needs 1.5x)
- Pivot (breakout trigger level): 305.9
- Entry: next session's open, only if volume confirms (price is already above pivot 305.9 on light volume)
- Volume vs 50-day avg: 0.98x
- ADR%: 2.5% | RS score: 95.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### COP — Energy [chart](https://www.tradingview.com/chart/?symbol=COP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 151.37
- Entry: pivot 151.37 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
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

### XOM — Energy [chart](https://www.tradingview.com/chart/?symbol=XOM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 184.54
- Entry: pivot 184.54 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.84x
- ADR%: 2.0% | RS score: 90.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CVX — Energy [chart](https://www.tradingview.com/chart/?symbol=CVX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 233.21
- Entry: pivot 233.21 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.67x
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

### EOG — Energy [chart](https://www.tradingview.com/chart/?symbol=EOG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 163.68
- Entry: pivot 163.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.84x
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

### OXY — Energy [chart](https://www.tradingview.com/chart/?symbol=OXY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 64.17
- Entry: pivot 64.17 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.4% | RS score: 85.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DVN — Energy [chart](https://www.tradingview.com/chart/?symbol=DVN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 51.64
- Entry: pivot 51.64 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.7% | RS score: 85.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### OKE — Energy [chart](https://www.tradingview.com/chart/?symbol=OKE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 96.36
- Entry: pivot 96.36 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.96x
- ADR%: 2.4% | RS score: 79.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### FANG — Energy [chart](https://www.tradingview.com/chart/?symbol=FANG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 207.13
- Entry: pivot 207.13 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.46x
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

### SLB — Energy [chart](https://www.tradingview.com/chart/?symbol=SLB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 54.08
- Entry: pivot 54.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.02x
- ADR%: 3.0% | RS score: 74.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### KMI — Energy [chart](https://www.tradingview.com/chart/?symbol=KMI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 34.43
- Entry: pivot 34.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 2.4% | RS score: 70.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Health Care** (27)

### MRNA — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 245.81
- Entry: pivot 245.81 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.5x
- ADR%: 10.1% | RS score: 99.0
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
  - ADR%: 10.1% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CRL — Health Care [chart](https://www.tradingview.com/chart/?symbol=CRL)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.86x avg, needs 1.5x)
- Pattern tag: Flag-Pivot
- Pivot (breakout trigger level): 373.98
- Entry: next session's open, only if volume confirms (price is already above pivot 373.98 on light volume)
- Volume vs 50-day avg: 0.86x
- ADR%: 4.3% | RS score: 97.0
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
  - ADR%: 4.3% (needs >= 3.0% volatility to qualify)
  - RS score: 97.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: Flag-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### HUM — Health Care [chart](https://www.tradingview.com/chart/?symbol=HUM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 433.5
- Entry: pivot 433.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
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
  - Riding the trend: yes, above 10/20-EMA

</details>

### RVTY — Health Care [chart](https://www.tradingview.com/chart/?symbol=RVTY)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.79x avg, needs 1.5x)
- Pivot (breakout trigger level): 165.33
- Entry: next session's open, only if volume confirms (price is already above pivot 165.33 on light volume)
- Volume vs 50-day avg: 0.79x
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

### CNC — Health Care [chart](https://www.tradingview.com/chart/?symbol=CNC)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 71.24
- Entry: pivot 71.24 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.22x
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
- Volume vs 50-day avg: 1.08x
- ADR%: 3.1% | RS score: 95.0
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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 95.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WST — Health Care [chart](https://www.tradingview.com/chart/?symbol=WST)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 403.64
- Entry: next session's open (pivot 403.64 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 3.19x
- ADR%: 2.3% | RS score: 94.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 3.19x the 50-day average (needs >= 1.5x)

</details>

### LLY — Health Care [chart](https://www.tradingview.com/chart/?symbol=LLY)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 1306.69
- Entry: next session's open (pivot 1306.69 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.85x
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
  - Setup: continuation breakout, volume 1.85x the 50-day average (needs >= 1.5x)

</details>

### VTRS — Health Care [chart](https://www.tradingview.com/chart/?symbol=VTRS)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.23x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 18.77
- Entry: next session's open, only if volume confirms (price is already above pivot 18.77 on light volume)
- Volume vs 50-day avg: 1.23x
- ADR%: 2.5% | RS score: 93.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### BIIB — Health Care [chart](https://www.tradingview.com/chart/?symbol=BIIB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 253.84
- Entry: pivot 253.84 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.06x
- ADR%: 3.0% | RS score: 93.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WAT — Health Care [chart](https://www.tradingview.com/chart/?symbol=WAT)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.13x avg, needs 1.5x)
- Pivot (breakout trigger level): 476.88
- Entry: next session's open, only if volume confirms (price is already above pivot 476.88 on light volume)
- Volume vs 50-day avg: 1.13x
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
  - Riding the trend: yes, above 10/20-EMA

</details>

### A — Health Care [chart](https://www.tradingview.com/chart/?symbol=A)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 181.48
- Entry: pivot 181.48 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.76x
- ADR%: 2.7% | RS score: 92.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AMGN — Health Care [chart](https://www.tradingview.com/chart/?symbol=AMGN)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.07x avg, needs 1.5x)
- Pivot (breakout trigger level): 451.83
- Entry: next session's open, only if volume confirms (price is already above pivot 451.83 on light volume)
- Volume vs 50-day avg: 1.07x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### LH — Health Care [chart](https://www.tradingview.com/chart/?symbol=LH)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 360.25
- Entry: next session's open (pivot 360.25 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.51x
- ADR%: 2.6% | RS score: 90.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 1.51x the 50-day average (needs >= 1.5x)

</details>

### IQV — Health Care [chart](https://www.tradingview.com/chart/?symbol=IQV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 279.36
- Entry: pivot 279.36 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.97x
- ADR%: 3.3% | RS score: 89.0
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
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### BDX — Health Care [chart](https://www.tradingview.com/chart/?symbol=BDX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 200.42
- Entry: pivot 200.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.31x
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

### TMO — Health Care [chart](https://www.tradingview.com/chart/?symbol=TMO)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.67x avg, needs 1.5x)
- Pivot (breakout trigger level): 704.15
- Entry: next session's open, only if volume confirms (price is already above pivot 704.15 on light volume)
- Volume vs 50-day avg: 0.67x
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

### ABBV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ABBV)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.95x avg, needs 1.5x)
- Pivot (breakout trigger level): 289.08
- Entry: next session's open, only if volume confirms (price is already above pivot 289.08 on light volume)
- Volume vs 50-day avg: 0.95x
- ADR%: 2.4% | RS score: 87.0
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
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### DGX — Health Care [chart](https://www.tradingview.com/chart/?symbol=DGX)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.89x avg, needs 1.5x)
- Pivot (breakout trigger level): 245.62
- Entry: next session's open, only if volume confirms (price is already above pivot 245.62 on light volume)
- Volume vs 50-day avg: 0.89x
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

### CAH — Health Care [chart](https://www.tradingview.com/chart/?symbol=CAH)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 257.55
- Entry: pivot 257.55 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.03x
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

### MTD — Health Care [chart](https://www.tradingview.com/chart/?symbol=MTD)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.63x avg, needs 1.5x)
- Pivot (breakout trigger level): 1698.47
- Entry: next session's open, only if volume confirms (price is already above pivot 1698.47 on light volume)
- Volume vs 50-day avg: 0.63x
- ADR%: 2.5% | RS score: 85.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### DVA — Health Care [chart](https://www.tradingview.com/chart/?symbol=DVA)
- Screens passed: B (Momentum)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 189.16
- Entry: next session's open (pivot 189.16 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 2.99x
- ADR%: 3.1% | RS score: 84.0
- Stage: Stage 2 (Uptrend)
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
  - RS score used: 84.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 2.99x the 50-day average (needs >= 1.5x)

</details>

### PFE — Health Care [chart](https://www.tradingview.com/chart/?symbol=PFE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 30.42
- Entry: pivot 30.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.09x
- ADR%: 1.9% | RS score: 83.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### JNJ — Health Care [chart](https://www.tradingview.com/chart/?symbol=JNJ)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.87x avg, needs 1.5x)
- Pivot (breakout trigger level): 271.04
- Entry: next session's open, only if volume confirms (price is already above pivot 271.04 on light volume)
- Volume vs 50-day avg: 0.87x
- ADR%: 2.2% | RS score: 83.0
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
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VRTX — Health Care [chart](https://www.tradingview.com/chart/?symbol=VRTX)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.38x avg, needs 1.5x)
- Pivot (breakout trigger level): 535.17
- Entry: next session's open, only if volume confirms (price is already above pivot 535.17 on light volume)
- Volume vs 50-day avg: 1.38x
- ADR%: 2.6% | RS score: 79.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### ELV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ELV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 445.28
- Entry: pivot 445.28 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.85x
- ADR%: 2.7% | RS score: 77.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### UNH — Health Care [chart](https://www.tradingview.com/chart/?symbol=UNH)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 424.98
- Entry: pivot 424.98 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.72x
- ADR%: 2.9% | RS score: 70.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Information Technology** (16)

### CRWD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 278.86
- Entry: pivot 278.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.9x
- ADR%: 4.7% | RS score: 98.0
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
  - ADR%: 4.7% (needs >= 3.0% volatility to qualify)
  - RS score: 98.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### NTAP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 239.18
- Entry: pivot 239.18 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.06x
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
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### AMD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AMD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 649.42
- Entry: pivot 649.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.84x
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

### PANW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PANW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 419.91
- Entry: pivot 419.91 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.22x
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

### DDOG — Information Technology [chart](https://www.tradingview.com/chart/?symbol=DDOG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 293.26
- Entry: pivot 293.26 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.16x
- ADR%: 4.9% | RS score: 96.0
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
  - ADR%: 4.9% (needs >= 3.0% volatility to qualify)
  - RS score: 96.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### ZBRA — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ZBRA)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 391.0
- Entry: pivot 391.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.02x
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
  - Riding the trend: no

</details>

### SWKS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=SWKS)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.63x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 87.23
- Entry: next session's open, only if volume confirms (price is already above pivot 87.23 on light volume)
- Volume vs 50-day avg: 0.63x
- ADR%: 4.1% | RS score: 94.0
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
  - ADR%: 4.1% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PLTR — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PLTR)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 209.05
- Entry: pivot 209.05 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.8x
- ADR%: 4.1% | RS score: 93.0
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
  - ADR%: 4.1% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### HPQ — Information Technology [chart](https://www.tradingview.com/chart/?symbol=HPQ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 34.09
- Entry: pivot 34.09 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.89x
- ADR%: 3.7% | RS score: 92.0
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
  - ADR%: 3.7% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: no

</details>

### ADI — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ADI)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.92x avg, needs 1.5x)
- Pivot (breakout trigger level): 428.27
- Entry: next session's open, only if volume confirms (price is already above pivot 428.27 on light volume)
- Volume vs 50-day avg: 0.92x
- ADR%: 3.0% | RS score: 91.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SHOP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=SHOP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 179.22
- Entry: pivot 179.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.53x
- ADR%: 4.1% | RS score: 86.0
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
  - ADR%: 4.1% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### AAPL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AAPL)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.06x avg, needs 1.5x)
- Pivot (breakout trigger level): 348.22
- Entry: next session's open, only if volume confirms (price is already above pivot 348.22 on light volume)
- Volume vs 50-day avg: 1.06x
- ADR%: 1.6% | RS score: 84.0
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
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CDW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CDW)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.59x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 165.11
- Entry: next session's open, only if volume confirms (price is already above pivot 165.11 on light volume)
- Volume vs 50-day avg: 0.59x
- ADR%: 3.2% | RS score: 77.0
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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### MSFT — Information Technology [chart](https://www.tradingview.com/chart/?symbol=MSFT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 543.45
- Entry: pivot 543.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.82x
- ADR%: 2.0% | RS score: 74.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### VRSN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=VRSN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 308.72
- Entry: pivot 308.72 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.94x
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

### ADP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=ADP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 307.94
- Entry: pivot 307.94 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.07x
- ADR%: 2.1% | RS score: 73.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Materials** (4)

### NUE — Materials [chart](https://www.tradingview.com/chart/?symbol=NUE)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.14x avg, needs 1.5x)
- Pivot (breakout trigger level): 271.79
- Entry: next session's open, only if volume confirms (price is already above pivot 271.79 on light volume)
- Volume vs 50-day avg: 1.14x
- ADR%: 2.9% | RS score: 91.0
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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### IFF — Materials [chart](https://www.tradingview.com/chart/?symbol=IFF)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 94.15
- Entry: pivot 94.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.66x
- ADR%: 1.9% | RS score: 86.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### STLD — Materials [chart](https://www.tradingview.com/chart/?symbol=STLD)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.79x avg, needs 1.5x)
- Pivot (breakout trigger level): 249.99
- Entry: next session's open, only if volume confirms (price is already above pivot 249.99 on light volume)
- Volume vs 50-day avg: 0.79x
- ADR%: 3.3% | RS score: 84.0
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
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### PKG — Materials [chart](https://www.tradingview.com/chart/?symbol=PKG)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.86x avg, needs 1.5x)
- Pivot (breakout trigger level): 253.74
- Entry: next session's open, only if volume confirms (price is already above pivot 253.74 on light volume)
- Volume vs 50-day avg: 0.86x
- ADR%: 2.0% | RS score: 72.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Consumer Staples** (7)

### KDP — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KDP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.35x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 35.19
- Entry: next session's open, only if volume confirms (price is already above pivot 35.19 on light volume)
- Volume vs 50-day avg: 1.35x
- ADR%: 2.1% | RS score: 84.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=PM)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.91x avg, needs 1.5x)
- Pivot (breakout trigger level): 205.58
- Entry: next session's open, only if volume confirms (price is already above pivot 205.58 on light volume)
- Volume vs 50-day avg: 0.91x
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

### MO — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=MO)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 76.07
- Entry: next session's open (pivot 76.07 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.58x
- ADR%: 1.9% | RS score: 82.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 1.58x the 50-day average (needs >= 1.5x)

</details>

### KO — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KO)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 95.34
- Entry: pivot 95.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.99x
- ADR%: 1.6% | RS score: 80.0
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
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SJM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=SJM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 133.39
- Entry: pivot 133.39 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.56x
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
  - Riding the trend: yes, above 10/20-EMA

</details>

### KVUE — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=KVUE)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 19.88
- Entry: pivot 19.88 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.57x
- ADR%: 1.6% | RS score: 76.0
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
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CHD — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=CHD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 108.86
- Entry: pivot 108.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.33x
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

**Industrials** (12)

### EXPD — Industrials [chart](https://www.tradingview.com/chart/?symbol=EXPD)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 199.64
- Entry: pivot 199.64 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.6x
- ADR%: 2.0% | RS score: 90.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 90.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### SWK — Industrials [chart](https://www.tradingview.com/chart/?symbol=SWK)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.13x avg, needs 1.5x)
- Pivot (breakout trigger level): 100.37
- Entry: next session's open, only if volume confirms (price is already above pivot 100.37 on light volume)
- Volume vs 50-day avg: 1.13x
- ADR%: 2.7% | RS score: 87.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### URI — Industrials [chart](https://www.tradingview.com/chart/?symbol=URI)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.83x avg, needs 1.5x)
- Pivot (breakout trigger level): 1174.61
- Entry: next session's open, only if volume confirms (price is already above pivot 1174.61 on light volume)
- Volume vs 50-day avg: 0.83x
- ADR%: 3.3% | RS score: 87.0
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
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 87.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### CSX — Industrials [chart](https://www.tradingview.com/chart/?symbol=CSX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 52.27
- Entry: pivot 52.27 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.26x
- ADR%: 1.8% | RS score: 84.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### JCI — Industrials [chart](https://www.tradingview.com/chart/?symbol=JCI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 158.76
- Entry: pivot 158.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.99x
- ADR%: 2.7% | RS score: 81.0
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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### NDSN — Industrials [chart](https://www.tradingview.com/chart/?symbol=NDSN)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 334.43
- Entry: pivot 334.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
- ADR%: 2.0% | RS score: 81.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EMR — Industrials [chart](https://www.tradingview.com/chart/?symbol=EMR)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.64x avg, needs 1.5x)
- Pivot (breakout trigger level): 167.71
- Entry: next session's open, only if volume confirms (price is already above pivot 167.71 on light volume)
- Volume vs 50-day avg: 0.64x
- ADR%: 2.5% | RS score: 80.0
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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### UNP — Industrials [chart](https://www.tradingview.com/chart/?symbol=UNP)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.81x avg, needs 1.5x)
- Pivot (breakout trigger level): 299.88
- Entry: next session's open, only if volume confirms (price is already above pivot 299.88 on light volume)
- Volume vs 50-day avg: 0.81x
- ADR%: 1.9% | RS score: 79.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### FAST — Industrials [chart](https://www.tradingview.com/chart/?symbol=FAST)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.88x avg, needs 1.5x)
- Pivot (breakout trigger level): 52.46
- Entry: next session's open, only if volume confirms (price is already above pivot 52.46 on light volume)
- Volume vs 50-day avg: 0.88x
- ADR%: 2.6% | RS score: 78.0
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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### GWW — Industrials [chart](https://www.tradingview.com/chart/?symbol=GWW)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.72x avg, needs 1.5x)
- Pivot (breakout trigger level): 1360.08
- Entry: next session's open, only if volume confirms (price is already above pivot 1360.08 on light volume)
- Volume vs 50-day avg: 0.72x
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

### IEX — Industrials [chart](https://www.tradingview.com/chart/?symbol=IEX)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 238.62
- Entry: next session's open (pivot 238.62 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 2.04x
- ADR%: 2.3% | RS score: 76.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 2.04x the 50-day average (needs >= 1.5x)

</details>

### DAL — Industrials [chart](https://www.tradingview.com/chart/?symbol=DAL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 83.89
- Entry: pivot 83.89 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.67x
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

**Consumer Discretionary** (3)

### BBY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=BBY)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.84x avg, needs 1.5x)
- Pivot (breakout trigger level): 99.87
- Entry: next session's open, only if volume confirms (price is already above pivot 99.87 on light volume)
- Volume vs 50-day avg: 0.84x
- ADR%: 3.0% | RS score: 93.0
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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### WSM — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=WSM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 260.8
- Entry: pivot 260.8 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
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
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### EBAY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=EBAY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 122.91
- Entry: pivot 122.91 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.67x
- ADR%: 2.8% | RS score: 76.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Financials** (11)

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

### FDS — Financials [chart](https://www.tradingview.com/chart/?symbol=FDS)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 335.45
- Entry: pivot 335.45 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.57x
- ADR%: 3.5% | RS score: 85.0
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
  - ADR%: 3.5% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### MET — Financials [chart](https://www.tradingview.com/chart/?symbol=MET)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 103.57
- Entry: pivot 103.57 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.95x
- ADR%: 1.9% | RS score: 82.0
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
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### AIZ — Financials [chart](https://www.tradingview.com/chart/?symbol=AIZ)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.87x avg, needs 1.5x)
- Pivot (breakout trigger level): 288.85
- Entry: next session's open, only if volume confirms (price is already above pivot 288.85 on light volume)
- Volume vs 50-day avg: 0.87x
- ADR%: 1.7% | RS score: 82.0
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
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### V — Financials [chart](https://www.tradingview.com/chart/?symbol=V)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 414.34
- Entry: pivot 414.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.25x
- ADR%: 1.8% | RS score: 79.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 79.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### EG — Financials [chart](https://www.tradingview.com/chart/?symbol=EG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 407.56
- Entry: pivot 407.56 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 4.32x
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

### PFG — Financials [chart](https://www.tradingview.com/chart/?symbol=PFG)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.02x avg, needs 1.5x)
- Pivot (breakout trigger level): 112.24
- Entry: next session's open, only if volume confirms (price is already above pivot 112.24 on light volume)
- Volume vs 50-day avg: 1.02x
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

### ALL — Financials [chart](https://www.tradingview.com/chart/?symbol=ALL)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 259.1
- Entry: pivot 259.1 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.62x
- ADR%: 2.0% | RS score: 74.0
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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

### MA — Financials [chart](https://www.tradingview.com/chart/?symbol=MA)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 633.21
- Entry: next session's open (pivot 633.21 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.53x
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
  - Setup: continuation breakout, volume 1.53x the 50-day average (needs >= 1.5x)

</details>

### NDAQ — Financials [chart](https://www.tradingview.com/chart/?symbol=NDAQ)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 105.55
- Entry: next session's open (pivot 105.55 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.52x
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
  - Setup: continuation breakout, volume 1.52x the 50-day average (needs >= 1.5x)

</details>

### CB — Financials [chart](https://www.tradingview.com/chart/?symbol=CB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 363.95
- Entry: pivot 363.95 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.14x
- ADR%: 1.6% | RS score: 71.0
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
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>

**Real Estate** (1)

### HST — Real Estate [chart](https://www.tradingview.com/chart/?symbol=HST)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.75x avg, needs 1.5x)
- Pivot (breakout trigger level): 25.27
- Entry: next session's open, only if volume confirms (price is already above pivot 25.27 on light volume)
- Volume vs 50-day avg: 0.75x
- ADR%: 2.1% | RS score: 89.0
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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA

</details>


## 4. Worth Watching

Market regime reads **defensive**, and **Energy** is leading with 71% of its names carrying RS 70+ and 14 clearing a screen outright today. On that basis, these 8 name(s) are worth watching:

- **MRNA** (Health Care) — VCP contraction (watch for trigger), RS 99.0, pivot 245.81. Entry: pivot 245.81 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **MPC** (Energy) — VCP contraction (watch for trigger), RS 98.0, pivot 484.92. Entry: pivot 484.92 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=MPC)
- **CRWD** (Information Technology) — VCP contraction (watch for trigger), RS 98.0, pivot 278.86. Entry: pivot 278.86 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- **NTAP** (Information Technology) — VCP contraction (watch for trigger) [VCP-Watch], RS 97.0, pivot 239.18. Entry: pivot 239.18 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- **AMD** (Information Technology) — VCP contraction (watch for trigger), RS 97.0, pivot 649.42. Entry: pivot 649.42 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=AMD)
- **APA** (Energy) — VCP contraction (watch for trigger), RS 97.0, pivot 51.9. Entry: pivot 51.9 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=APA)
- **PANW** (Information Technology) — VCP contraction (watch for trigger), RS 96.0, pivot 419.91. Entry: pivot 419.91 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=PANW)
- **DDOG** (Information Technology) — VCP contraction (watch for trigger), RS 96.0, pivot 293.26. Entry: pivot 293.26 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=DDOG)

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

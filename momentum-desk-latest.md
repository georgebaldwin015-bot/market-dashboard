# Momentum Desk — Daily Report (2026-08-21)
*Educational/informational output modeling Mark Minervini's and Kristjan "Qullamaggie" Kullamägi's publicly
described methodologies. Not personalized financial advice; this is not a licensed advisor. Confirm every
setup on an actual chart before acting.*
*Data source: Yahoo Finance (via yfinance), end-of-day bars. Universe defined in `universe.csv` — edit that file to expand coverage. Sector/industry groupings are derived live from Yahoo Finance and shared with the Daily Market Report tab via `industry_map.py`.*
## What's Going On

The market is holding an uptrend but losing some of its edge, with breadth reading 58% of the scanned universe above its 50-day moving average and 5 distribution days in the past month -- an elevated count worth watching. Zooming out, breadth has been roughly flat over the last 60 sessions (+1.4 pt change in % above the 50-day MA) and deteriorating over the last two weeks (-7.8 pt), while SPY is climbing (+1.7% over 60 sessions, -0.9% over the last two weeks). Momentum under the surface is leaning firmly long -- 22 name(s) hit a fresh 52-week high today against 6 breaking down to a fresh 52-week low. Energy is leading, with 62% of its 21 scanned names carrying an RS score of 70+ and 10 clearing a screen outright today, with Health Care also showing real strength. It's being driven by names like HAL and EQT. With 73 name(s) clearing a screen across 10 sector(s), there's a workable watchlist below -- see Worth Watching for the shortlist tied to today's regime and themes.

## 1. Market Pulse

SPY close: 765.72 | 10-day MA: 770.78 | 20-day MA: 762.33

**Caution** — 10-day above 20-day but losing upward slope. Trade smaller, tighter.

- Breadth: 58% of the scanned universe above its 50-day MA, 72% above its 200-day MA.
- 52-week breakouts vs breakdowns today: 22 breakouts / 6 breakdowns (out of 519 names evaluated).
- Distribution days (SPY, trailing 25 sessions): 5. Elevated -- a headwind even if price is holding up.
- Follow-through day: none in the recent window.

## 2. Leading Themes

Ranked by breadth of strength (share of each sector's names with an RS score >= 70), not raw average price change -- see Risk & Process Notes.

| Sector | Names Scanned | Median RS | % RS >= 70 | Clearing a Screen |
|---|---|---|---|---|
| Energy | 21 | 75 | 62% | 10 |
| Health Care | 60 | 69 | 50% | 26 |
| Information Technology | 90 | 62 | 47% | 15 |
| Materials | 26 | 58 | 31% | 9 |
| Financials | 70 | 56 | 30% | 27 |
| Industrials | 77 | 57 | 30% | 22 |
| Consumer Discretionary | 53 | 40 | 23% | 9 |
| Real Estate | 31 | 41 | 10% | 5 |
| Communication Services | 22 | 34 | 9% | 1 |
| Consumer Staples | 31 | 37 | 6% | 3 |
| Utilities | 31 | 23 | 0% | 0 |
| Unknown | 3 | 5 | 0% | 0 |

**Leading theme: Energy** — 62% of its 21 scanned names carry an RS score of 70+, and 10 name(s) are clearing a screen outright today.

## 3. Leading Stocks

**Leader spotlight** — the strongest names driving today's leading themes:

- **MRNA** (Health Care) — RS 99.0, Continuation breakout (confirmed) [Episodic Pivot-Breakout], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **PANW** (Information Technology) — RS 96.0, VCP contraction (watch for trigger) [VCP-Watch], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=PANW)
- **CRWD** (Information Technology) — RS 94.0, VCP contraction (watch for trigger), Stage: Stage 1 (Basing). [chart](https://www.tradingview.com/chart/?symbol=CRWD)

**Energy** (2)

### HAL — Energy [chart](https://www.tradingview.com/chart/?symbol=HAL)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 35.69
- Entry: pivot 35.69 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
- ADR%: 2.6% | RS score: 61.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 61.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 61.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### EQT — Energy [chart](https://www.tradingview.com/chart/?symbol=EQT)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 54.42
- Entry: pivot 54.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 2.4% | RS score: 16.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 16.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 16.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Health Care** (10)

### MRNA — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- Screens passed: A (Trend Template) + B (Momentum)
- Setup: Continuation breakout (confirmed)
- Pattern tag: Episodic Pivot-Breakout
- Pivot (breakout trigger level): 64.46
- Entry: next session's open (pivot 64.46 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 5.9x
- ADR%: 8.7% | RS score: 99.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 8.7% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 5.9x the 50-day average (needs >= 1.5x)
**Pattern tag: Episodic Pivot-Breakout** (VCP/Flag/EP classification, additive to the screens above)

</details>

### A — Health Care [chart](https://www.tradingview.com/chart/?symbol=A)
- Screens passed: VCP forming (pre-breakout)
- Setup: Cleared pivot on light volume (unconfirmed — 1.3x avg, needs 1.5x)
- Pivot (breakout trigger level): 156.3
- Entry: next session's open, only if volume confirms (price is already above pivot 156.3 on light volume)
- Volume vs 50-day avg: 1.3x
- ADR%: 2.4% | RS score: 86.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 86.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 86.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### WST — Health Care [chart](https://www.tradingview.com/chart/?symbol=WST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 354.07
- Entry: pivot 354.07 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.57x
- ADR%: 2.1% | RS score: 85.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 85.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### LH — Health Care [chart](https://www.tradingview.com/chart/?symbol=LH)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.61x avg, needs 1.5x)
- Pivot (breakout trigger level): 332.81
- Entry: next session's open, only if volume confirms (price is already above pivot 332.81 on light volume)
- Volume vs 50-day avg: 0.61x
- ADR%: 2.6% | RS score: 82.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### BIIB — Health Care [chart](https://www.tradingview.com/chart/?symbol=BIIB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 221.56
- Entry: pivot 221.56 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.57x
- ADR%: 2.9% | RS score: 80.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### WAT — Health Care [chart](https://www.tradingview.com/chart/?symbol=WAT)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 416.15
- Entry: pivot 416.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.76x
- ADR%: 3.1% | RS score: 74.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 74.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### UNH — Health Care [chart](https://www.tradingview.com/chart/?symbol=UNH)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 428.79
- Entry: pivot 428.79 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.89x
- ADR%: 2.4% | RS score: 70.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 70.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### ELV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ELV)
- Screens passed: VCP forming (pre-breakout)
- Setup: Cleared pivot on light volume (unconfirmed — 0.54x avg, needs 1.5x)
- Pivot (breakout trigger level): 400.32
- Entry: next session's open, only if volume confirms (price is already above pivot 400.32 on light volume)
- Volume vs 50-day avg: 0.54x
- ADR%: 2.6% | RS score: 63.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 63.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 63.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### EW — Health Care [chart](https://www.tradingview.com/chart/?symbol=EW)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 93.66
- Entry: pivot 93.66 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.46x
- ADR%: 2.3% | RS score: 47.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 47.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 47.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CI — Health Care [chart](https://www.tradingview.com/chart/?symbol=CI)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 301.06
- Entry: pivot 301.06 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 2.5% | RS score: 24.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 24.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 24.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Information Technology** (8)

### PANW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PANW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 396.0
- Entry: pivot 396.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
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
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CRWD — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 225.53
- Entry: pivot 225.53 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.85x
- ADR%: 4.4% | RS score: 94.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 94.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.4% (needs >= 3.0% volatility to qualify)
  - RS score: 94.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### XYZ — Information Technology [chart](https://www.tradingview.com/chart/?symbol=XYZ)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 84.64
- Entry: pivot 84.64 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.25x
- ADR%: 3.1% | RS score: 84.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### CPAY — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CPAY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 425.24
- Entry: pivot 425.24 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.42x
- ADR%: 2.7% | RS score: 83.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.7% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### TXN — Information Technology [chart](https://www.tradingview.com/chart/?symbol=TXN)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 286.08
- Entry: pivot 286.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.65x
- ADR%: 3.3% | RS score: 71.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 71.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.3% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### AAPL — Information Technology [chart](https://www.tradingview.com/chart/?symbol=AAPL)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 339.79
- Entry: pivot 339.79 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.74x
- ADR%: 2.1% | RS score: 61.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 61.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 61.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### TDY — Information Technology [chart](https://www.tradingview.com/chart/?symbol=TDY)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 691.3
- Entry: pivot 691.3 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.61x
- ADR%: 2.2% | RS score: 49.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 49.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 49.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### CDNS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CDNS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 344.72
- Entry: pivot 344.72 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.91x
- ADR%: 3.2% | RS score: 20.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 20.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 20.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Materials** (8)

### FCX — Materials [chart](https://www.tradingview.com/chart/?symbol=FCX)
- Screens passed: A (Trend Template) + B (Momentum)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 71.22
- Entry: next session's open (pivot 71.22 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.94x
- ADR%: 3.6% | RS score: 93.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 3.6% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 1.94x the 50-day average (needs >= 1.5x)
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### SW — Materials [chart](https://www.tradingview.com/chart/?symbol=SW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 50.34
- Entry: pivot 50.34 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.49x
- ADR%: 3.2% | RS score: 82.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 82.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PKG — Materials [chart](https://www.tradingview.com/chart/?symbol=PKG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 257.43
- Entry: pivot 257.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.55x
- ADR%: 2.1% | RS score: 72.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### DOW — Materials [chart](https://www.tradingview.com/chart/?symbol=DOW)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 32.9
- Entry: pivot 32.9 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 3.2% | RS score: 65.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 65.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 65.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### BALL — Materials [chart](https://www.tradingview.com/chart/?symbol=BALL)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 66.89
- Entry: pivot 66.89 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.41x
- ADR%: 2.1% | RS score: 62.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 62.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 62.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### IP — Materials [chart](https://www.tradingview.com/chart/?symbol=IP)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 43.59
- Entry: pivot 43.59 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.42x
- ADR%: 3.1% | RS score: 60.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 60.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.1% (needs >= 3.0% volatility to qualify)
  - RS score: 60.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PPG — Materials [chart](https://www.tradingview.com/chart/?symbol=PPG)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 118.98
- Entry: pivot 118.98 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.4x
- ADR%: 2.4% | RS score: 42.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 42.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 42.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### SHW — Materials [chart](https://www.tradingview.com/chart/?symbol=SHW)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 369.73
- Entry: pivot 369.73 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.5x
- ADR%: 2.2% | RS score: 36.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 36.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 36.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Financials** (20)

### STT — Financials [chart](https://www.tradingview.com/chart/?symbol=STT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 193.04
- Entry: pivot 193.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.54x
- ADR%: 2.2% | RS score: 92.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 92.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### BNY — Financials [chart](https://www.tradingview.com/chart/?symbol=BNY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 164.27
- Entry: pivot 164.27 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.48x
- ADR%: 1.8% | RS score: 89.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 89.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### MS — Financials [chart](https://www.tradingview.com/chart/?symbol=MS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 218.38
- Entry: pivot 218.38 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.59x
- ADR%: 2.4% | RS score: 80.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 80.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 80.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CFG — Financials [chart](https://www.tradingview.com/chart/?symbol=CFG)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 74.73
- Entry: pivot 74.73 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.81x
- ADR%: 2.1% | RS score: 78.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 78.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### TRV — Financials [chart](https://www.tradingview.com/chart/?symbol=TRV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 397.22
- Entry: pivot 397.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 2.0% | RS score: 78.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 78.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### USB — Financials [chart](https://www.tradingview.com/chart/?symbol=USB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 65.42
- Entry: pivot 65.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.51x
- ADR%: 1.7% | RS score: 76.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 76.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 76.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### SCHW — Financials [chart](https://www.tradingview.com/chart/?symbol=SCHW)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 0.56x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 111.68
- Entry: next session's open, only if volume confirms (price is already above pivot 111.68 on light volume)
- Volume vs 50-day avg: 0.56x
- ADR%: 1.8% | RS score: 74.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 74.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

### GS — Financials [chart](https://www.tradingview.com/chart/?symbol=GS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1061.23
- Entry: pivot 1061.23 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.22x
- ADR%: 2.6% | RS score: 73.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 73.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 73.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### C — Financials [chart](https://www.tradingview.com/chart/?symbol=C)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 139.33
- Entry: pivot 139.33 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 2.3% | RS score: 72.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 72.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### AMP — Financials [chart](https://www.tradingview.com/chart/?symbol=AMP)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 570.68
- Entry: pivot 570.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
- ADR%: 1.9% | RS score: 70.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 70.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### FITB — Financials [chart](https://www.tradingview.com/chart/?symbol=FITB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 58.06
- Entry: pivot 58.06 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.96x
- ADR%: 1.9% | RS score: 68.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 68.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 68.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### MTB — Financials [chart](https://www.tradingview.com/chart/?symbol=MTB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 254.09
- Entry: pivot 254.09 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
- ADR%: 1.6% | RS score: 68.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 68.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 68.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### JPM — Financials [chart](https://www.tradingview.com/chart/?symbol=JPM)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 365.18
- Entry: pivot 365.18 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 1.7% | RS score: 66.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 66.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 66.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### RF — Financials [chart](https://www.tradingview.com/chart/?symbol=RF)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 31.95
- Entry: pivot 31.95 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.53x
- ADR%: 1.7% | RS score: 62.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 62.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 62.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### CB — Financials [chart](https://www.tradingview.com/chart/?symbol=CB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 363.5
- Entry: pivot 363.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.08x
- ADR%: 1.6% | RS score: 50.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 50.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 50.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### TFC — Financials [chart](https://www.tradingview.com/chart/?symbol=TFC)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 53.1
- Entry: pivot 53.1 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.44x
- ADR%: 1.7% | RS score: 48.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 48.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 48.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### BLK — Financials [chart](https://www.tradingview.com/chart/?symbol=BLK)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 1182.84
- Entry: pivot 1182.84 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.5x
- ADR%: 1.9% | RS score: 47.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 47.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 47.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### L — Financials [chart](https://www.tradingview.com/chart/?symbol=L)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 119.33
- Entry: pivot 119.33 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.42x
- ADR%: 1.7% | RS score: 34.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 34.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 34.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### HIG — Financials [chart](https://www.tradingview.com/chart/?symbol=HIG)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 145.68
- Entry: pivot 145.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.41x
- ADR%: 1.7% | RS score: 28.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 28.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 28.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### WRB — Financials [chart](https://www.tradingview.com/chart/?symbol=WRB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 76.17
- Entry: pivot 76.17 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.56x
- ADR%: 1.8% | RS score: 23.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 2/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 23.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 23.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Industrials** (14)

### WAB — Industrials [chart](https://www.tradingview.com/chart/?symbol=WAB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 305.47
- Entry: pivot 305.47 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GEV — Industrials [chart](https://www.tradingview.com/chart/?symbol=GEV)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1079.0
- Entry: pivot 1079.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.42x
- ADR%: 4.3% | RS score: 81.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 81.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.3% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### URI — Industrials [chart](https://www.tradingview.com/chart/?symbol=URI)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1164.82
- Entry: pivot 1164.82 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.96x
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
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### DE — Industrials [chart](https://www.tradingview.com/chart/?symbol=DE)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 639.84
- Entry: next session's open (pivot 639.84 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 1.77x
- ADR%: 3.0% | RS score: 75.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 1.77x the 50-day average (needs >= 1.5x)

</details>

### RTX — Industrials [chart](https://www.tradingview.com/chart/?symbol=RTX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 225.49
- Entry: pivot 225.49 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.95x
- ADR%: 2.1% | RS score: 70.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 70.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### FAST — Industrials [chart](https://www.tradingview.com/chart/?symbol=FAST)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 52.38
- Entry: pivot 52.38 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.53x
- ADR%: 2.2% | RS score: 65.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 65.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 65.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GE — Industrials [chart](https://www.tradingview.com/chart/?symbol=GE)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 381.22
- Entry: pivot 381.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.82x
- ADR%: 2.6% | RS score: 64.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 64.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 64.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### MMM — Industrials [chart](https://www.tradingview.com/chart/?symbol=MMM)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 183.78
- Entry: pivot 183.78 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.57x
- ADR%: 2.1% | RS score: 60.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 60.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 60.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### SNA — Industrials [chart](https://www.tradingview.com/chart/?symbol=SNA)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 416.72
- Entry: pivot 416.72 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
- ADR%: 1.7% | RS score: 59.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 59.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 59.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### UAL — Industrials [chart](https://www.tradingview.com/chart/?symbol=UAL)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 132.76
- Entry: pivot 132.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.65x
- ADR%: 2.9% | RS score: 57.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 57.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 57.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### ALLE — Industrials [chart](https://www.tradingview.com/chart/?symbol=ALLE)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 168.94
- Entry: pivot 168.94 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.58x
- ADR%: 2.3% | RS score: 50.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 50.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 50.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CTAS — Industrials [chart](https://www.tradingview.com/chart/?symbol=CTAS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 215.97
- Entry: pivot 215.97 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
- ADR%: 2.1% | RS score: 48.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 48.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 48.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### DOV — Industrials [chart](https://www.tradingview.com/chart/?symbol=DOV)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 211.13
- Entry: pivot 211.13 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.48x
- ADR%: 1.8% | RS score: 30.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 30.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 30.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### HON — Industrials [chart](https://www.tradingview.com/chart/?symbol=HON)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 248.05
- Entry: pivot 248.05 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.81x
- ADR%: 2.5% | RS score: 19.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 19.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 19.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Consumer Discretionary** (6)

### CASY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=CASY)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 871.0
- Entry: pivot 871.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
- ADR%: 2.9% | RS score: 83.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ✅ RS score >= 70
  - RS score used: 83.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GM — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=GM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 90.3
- Entry: pivot 90.3 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.59x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### WSM — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=WSM)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 251.78
- Entry: pivot 251.78 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.61x
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
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GPC — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=GPC)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 135.63
- Entry: pivot 135.63 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.54x
- ADR%: 2.4% | RS score: 70.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### HAS — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=HAS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 96.32
- Entry: pivot 96.32 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 2.5% | RS score: 52.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 52.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 52.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PHM — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=PHM)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 134.75
- Entry: pivot 134.75 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.56x
- ADR%: 2.8% | RS score: 42.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 42.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 42.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Real Estate** (3)

### PLD — Real Estate [chart](https://www.tradingview.com/chart/?symbol=PLD)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 147.63
- Entry: pivot 147.63 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.51x
- ADR%: 1.6% | RS score: 51.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 6/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 51.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 51.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### DLR — Real Estate [chart](https://www.tradingview.com/chart/?symbol=DLR)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 200.15
- Entry: pivot 200.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.31x
- ADR%: 2.6% | RS score: 49.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 49.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 49.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### AVB — Real Estate [chart](https://www.tradingview.com/chart/?symbol=AVB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 195.5
- Entry: pivot 195.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.0x
- ADR%: 1.4% | RS score: 35.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 5/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 35.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.4% (needs >= 3.0% volatility to qualify)
  - RS score: 35.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Communication Services** (1)

### T — Communication Services [chart](https://www.tradingview.com/chart/?symbol=T)
- Screens passed: VCP forming (pre-breakout)
- Setup: Cleared pivot on light volume (unconfirmed — 0.32x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 25.15
- Entry: next session's open, only if volume confirms (price is already above pivot 25.15 on light volume)
- Volume vs 50-day avg: 0.32x
- ADR%: 2.1% | RS score: 21.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 4/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 21.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 21.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Pivot** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Consumer Staples** (1)

### PM — Consumer Staples [chart](https://www.tradingview.com/chart/?symbol=PM)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 200.17
- Entry: pivot 200.17 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.6x
- ADR%: 2.2% | RS score: 46.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 7/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ✅ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 46.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 46.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>


## 4. Worth Watching

Market regime reads **caution**, and **Energy** is leading with 62% of its names carrying RS 70+ and 10 clearing a screen outright today. On that basis, these 8 name(s) are worth watching:

- **MRNA** (Health Care) — Continuation breakout (confirmed) [Episodic Pivot-Breakout], RS 99.0, pivot 64.46. Entry: next session's open (pivot 64.46 already cleared at today's close -- don't chase that level). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **PANW** (Information Technology) — VCP contraction (watch for trigger) [VCP-Watch], RS 96.0, pivot 396.0. Entry: pivot 396.0 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=PANW)
- **CRWD** (Information Technology) — VCP contraction (watch for trigger), RS 94.0, pivot 225.53. Entry: pivot 225.53 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- **FCX** (Materials) — Continuation breakout (confirmed), RS 93.0, pivot 71.22. Entry: next session's open (pivot 71.22 already cleared at today's close -- don't chase that level). [chart](https://www.tradingview.com/chart/?symbol=FCX)
- **STT** (Financials) — VCP contraction (watch for trigger) [VCP-Watch], RS 92.0, pivot 193.04. Entry: pivot 193.04 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=STT)
- **BNY** (Financials) — VCP contraction (watch for trigger), RS 89.0, pivot 164.27. Entry: pivot 164.27 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=BNY)
- **A** (Health Care) — Cleared pivot on light volume (unconfirmed — 1.3x avg, needs 1.5x), RS 86.0, pivot 156.3. Entry: next session's open, only if volume confirms (price is already above pivot 156.3 on light volume). [chart](https://www.tradingview.com/chart/?symbol=A)
- **WAB** (Industrials) — VCP contraction (watch for trigger), RS 86.0, pivot 305.47. Entry: pivot 305.47 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=WAB)

## 5. Other Setups (context)


**Extended / parabolic-short context (not a trade signal by itself):**
- MRNA (Health Care) [chart](https://www.tradingview.com/chart/?symbol=MRNA) — 114.7% above 50-day MA, +145.3% over the last 10 sessions.

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

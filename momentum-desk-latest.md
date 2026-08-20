# Momentum Desk — Daily Report (2026-08-20)
*Educational/informational output modeling Mark Minervini's and Kristjan "Qullamaggie" Kullamägi's publicly
described methodologies. Not personalized financial advice; this is not a licensed advisor. Confirm every
setup on an actual chart before acting.*
*Data source: Yahoo Finance (via yfinance), end-of-day bars. Universe defined in `universe.csv` — edit that file to expand coverage. Sector/industry groupings are derived live from Yahoo Finance and shared with the Daily Market Report tab via `industry_map.py`.*
## What's Going On

The market is in a confirmed uptrend, with breadth reading 55% of the scanned universe above its 50-day moving average and a manageable 4 distribution days in the past month. Zooming out, breadth has been roughly flat over the last 60 sessions (-1.6 pt change in % above the 50-day MA) and deteriorating over the last two weeks (-11.8 pt), while SPY is climbing (+1.9% over 60 sessions, -1.4% over the last two weeks). That trend is broadly consistent with today's snapshot, not diverging from it. Momentum under the surface is leaning firmly long -- 15 name(s) hit a fresh 52-week high today against 5 breaking down to a fresh 52-week low. Energy is leading, with 67% of its 21 scanned names carrying an RS score of 70+ and 10 clearing a screen outright today, with Health Care also showing real strength. It's being driven by names like EQT. With 58 name(s) clearing a screen across 10 sector(s), there's a workable watchlist below -- see Worth Watching for the shortlist tied to today's regime and themes.

## 1. Market Pulse

SPY close: 762.60 | 10-day MA: 771.53 | 20-day MA: 760.99

**Constructive** — 10-day MA above the 20-day and rising. Long setups get the benefit of the doubt.

- Breadth: 55% of the scanned universe above its 50-day MA, 73% above its 200-day MA.
- 52-week breakouts vs breakdowns today: 15 breakouts / 5 breakdowns (out of 519 names evaluated).
- Distribution days (SPY, trailing 25 sessions): 4.
- Follow-through day: none in the recent window.

## 2. Leading Themes

Ranked by breadth of strength (share of each sector's names with an RS score >= 70), not raw average price change -- see Risk & Process Notes.

| Sector | Names Scanned | Median RS | % RS >= 70 | Clearing a Screen |
|---|---|---|---|---|
| Energy | 21 | 75 | 67% | 10 |
| Health Care | 60 | 70 | 52% | 22 |
| Information Technology | 90 | 63 | 46% | 14 |
| Materials | 26 | 57 | 31% | 5 |
| Industrials | 77 | 57 | 29% | 20 |
| Financials | 70 | 54 | 27% | 25 |
| Consumer Discretionary | 53 | 38 | 25% | 8 |
| Real Estate | 31 | 45 | 13% | 7 |
| Communication Services | 22 | 36 | 9% | 1 |
| Consumer Staples | 31 | 36 | 6% | 3 |
| Utilities | 31 | 27 | 0% | 0 |
| Unknown | 3 | 4 | 0% | 0 |

**Leading theme: Energy** — 67% of its 21 scanned names carry an RS score of 70+, and 10 name(s) are clearing a screen outright today.

## 3. Leading Stocks

**Leader spotlight** — the strongest names driving today's leading themes:

- **MRNA** (Health Care) — RS 99.0, Continuation breakout (confirmed) [Episodic Pivot-Breakout], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **NTAP** (Information Technology) — RS 96.0, VCP contraction (watch for trigger) [Flag-Watch], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- **PANW** (Information Technology) — RS 96.0, VCP contraction (watch for trigger) [VCP-Watch], Stage: Stage 2 (Uptrend). [chart](https://www.tradingview.com/chart/?symbol=PANW)

**Energy** (1)

### EQT — Energy [chart](https://www.tradingview.com/chart/?symbol=EQT)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 54.42
- Entry: pivot 54.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.55x
- ADR%: 2.4% | RS score: 18.0
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
  - RS score used: 18.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 18.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Health Care** (7)

### MRNA — Health Care [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- Screens passed: A (Trend Template) + B (Momentum)
- Setup: Continuation breakout (confirmed)
- Pattern tag: Episodic Pivot-Breakout
- Pivot (breakout trigger level): 64.46
- Entry: next session's open (pivot 64.46 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 7.48x
- ADR%: 8.1% | RS score: 99.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 8.1% (needs >= 3.0% volatility to qualify)
  - RS score: 99.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
  - Setup: continuation breakout, volume 7.48x the 50-day average (needs >= 1.5x)
**Pattern tag: Episodic Pivot-Breakout** (VCP/Flag/EP classification, additive to the screens above)

</details>

### WST — Health Care [chart](https://www.tradingview.com/chart/?symbol=WST)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 355.25
- Entry: pivot 355.25 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.63x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### DGX — Health Care [chart](https://www.tradingview.com/chart/?symbol=DGX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 241.76
- Entry: pivot 241.76 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.98x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### BIIB — Health Care [chart](https://www.tradingview.com/chart/?symbol=BIIB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 221.56
- Entry: pivot 221.56 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.66x
- ADR%: 2.9% | RS score: 81.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.9% (needs >= 3.0% volatility to qualify)
  - RS score: 81.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### UNH — Health Care [chart](https://www.tradingview.com/chart/?symbol=UNH)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 428.79
- Entry: pivot 428.79 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.62x
- ADR%: 2.4% | RS score: 66.0
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
  - RS score used: 66.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 66.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### ELV — Health Care [chart](https://www.tradingview.com/chart/?symbol=ELV)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 400.32
- Entry: pivot 400.32 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.29x
- ADR%: 2.6% | RS score: 59.0
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
  - RS score used: 59.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 59.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CI — Health Care [chart](https://www.tradingview.com/chart/?symbol=CI)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 301.06
- Entry: pivot 301.06 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.5x
- ADR%: 2.5% | RS score: 21.0
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
  - RS score used: 21.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 21.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Information Technology** (5)

### NTAP — Information Technology [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: Flag-Watch
- Pivot (breakout trigger level): 207.08
- Entry: pivot 207.08 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: Flag-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### PANW — Information Technology [chart](https://www.tradingview.com/chart/?symbol=PANW)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 396.0
- Entry: pivot 396.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.68x
- ADR%: 4.1% | RS score: 96.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 4.1% (needs >= 3.0% volatility to qualify)
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
- Volume vs 50-day avg: 0.91x
- ADR%: 4.4% | RS score: 93.0
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
  - RS score used: 93.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 4.4% (needs >= 3.0% volatility to qualify)
  - RS score: 93.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### TDY — Information Technology [chart](https://www.tradingview.com/chart/?symbol=TDY)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 691.3
- Entry: pivot 691.3 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.57x
- ADR%: 2.3% | RS score: 49.0
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
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 49.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CDNS — Information Technology [chart](https://www.tradingview.com/chart/?symbol=CDNS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 344.72
- Entry: pivot 344.72 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.73x
- ADR%: 3.2% | RS score: 17.0
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
  - RS score used: 17.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.2% (needs >= 3.0% volatility to qualify)
  - RS score: 17.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Materials** (3)

### FCX — Materials [chart](https://www.tradingview.com/chart/?symbol=FCX)
- Screens passed: A (Trend Template)
- Setup: Cleared pivot on light volume (unconfirmed — 1.0x avg, needs 1.5x)
- Pivot (breakout trigger level): 70.51
- Entry: next session's open, only if volume confirms (price is already above pivot 70.51 on light volume)
- Volume vs 50-day avg: 1.0x
- ADR%: 3.5% | RS score: 91.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 3.5% (needs >= 3.0% volatility to qualify)
  - RS score: 91.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### PKG — Materials [chart](https://www.tradingview.com/chart/?symbol=PKG)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 257.43
- Entry: pivot 257.43 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.63x
- ADR%: 2.5% | RS score: 71.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

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
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
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
- Volume vs 50-day avg: 0.57x
- ADR%: 2.3% | RS score: 39.0
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
  - RS score used: 39.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 39.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Industrials** (13)

### NDSN — Industrials [chart](https://www.tradingview.com/chart/?symbol=NDSN)
- Screens passed: A (Trend Template)
- Setup: Continuation breakout (confirmed)
- Pivot (breakout trigger level): 311.36
- Entry: next session's open (pivot 311.36 already cleared at today's close -- don't chase that level)
- Volume vs 50-day avg: 3.01x
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
  - Setup: continuation breakout, volume 3.01x the 50-day average (needs >= 1.5x)

</details>

### WAB — Industrials [chart](https://www.tradingview.com/chart/?symbol=WAB)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 305.47
- Entry: pivot 305.47 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.79x
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
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GEV — Industrials [chart](https://www.tradingview.com/chart/?symbol=GEV)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1079.0
- Entry: pivot 1079.0 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
- ADR%: 4.4% | RS score: 83.0
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
  - ADR%: 4.4% (needs >= 3.0% volatility to qualify)
  - RS score: 83.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### URI — Industrials [chart](https://www.tradingview.com/chart/?symbol=URI)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 1164.82
- Entry: pivot 1164.82 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.1x
- ADR%: 2.8% | RS score: 77.0
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
  - RS score used: 77.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### RTX — Industrials [chart](https://www.tradingview.com/chart/?symbol=RTX)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 225.49
- Entry: pivot 225.49 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
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
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GE — Industrials [chart](https://www.tradingview.com/chart/?symbol=GE)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 381.22
- Entry: pivot 381.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
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

### FAST — Industrials [chart](https://www.tradingview.com/chart/?symbol=FAST)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 52.38
- Entry: pivot 52.38 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.6x
- ADR%: 2.2% | RS score: 63.0
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
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 63.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### MMM — Industrials [chart](https://www.tradingview.com/chart/?symbol=MMM)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 183.78
- Entry: pivot 183.78 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 2.1% | RS score: 62.0
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
  - RS score used: 62.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 62.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### SNA — Industrials [chart](https://www.tradingview.com/chart/?symbol=SNA)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 416.72
- Entry: pivot 416.72 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.53x
- ADR%: 1.8% | RS score: 59.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 59.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### LMT — Industrials [chart](https://www.tradingview.com/chart/?symbol=LMT)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 608.68
- Entry: pivot 608.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.92x
- ADR%: 2.5% | RS score: 58.0
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
  - RS score used: 58.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 58.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CTAS — Industrials [chart](https://www.tradingview.com/chart/?symbol=CTAS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 215.97
- Entry: pivot 215.97 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.84x
- ADR%: 2.1% | RS score: 51.0
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
  - RS score used: 51.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.1% (needs >= 3.0% volatility to qualify)
  - RS score: 51.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### DOV — Industrials [chart](https://www.tradingview.com/chart/?symbol=DOV)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 211.13
- Entry: pivot 211.13 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.69x
- ADR%: 1.9% | RS score: 25.0
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
  - RS score used: 25.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 25.0 (needs >= 80 for this screen)
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
- Volume vs 50-day avg: 0.54x
- ADR%: 2.6% | RS score: 22.0
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
  - RS score used: 22.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 22.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Financials** (18)

### STT — Financials [chart](https://www.tradingview.com/chart/?symbol=STT)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 193.04
- Entry: pivot 193.04 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.6x
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
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### BNY — Financials [chart](https://www.tradingview.com/chart/?symbol=BNY)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 164.27
- Entry: pivot 164.27 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.36x
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

### TRV — Financials [chart](https://www.tradingview.com/chart/?symbol=TRV)
- Screens passed: A (Trend Template)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 397.22
- Entry: pivot 397.22 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.63x
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
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### USB — Financials [chart](https://www.tradingview.com/chart/?symbol=USB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 65.42
- Entry: pivot 65.42 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.5x
- ADR%: 1.7% | RS score: 77.0
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
  - RS score used: 77.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 77.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### MS — Financials [chart](https://www.tradingview.com/chart/?symbol=MS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 218.38
- Entry: pivot 218.38 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.66x
- ADR%: 2.4% | RS score: 75.0
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
  - RS score used: 75.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.4% (needs >= 3.0% volatility to qualify)
  - RS score: 75.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### SCHW — Financials [chart](https://www.tradingview.com/chart/?symbol=SCHW)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 111.68
- Entry: pivot 111.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.54x
- ADR%: 1.7% | RS score: 71.0
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
  - RS score used: 71.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 71.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### FITB — Financials [chart](https://www.tradingview.com/chart/?symbol=FITB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 58.06
- Entry: pivot 58.06 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.93x
- ADR%: 1.9% | RS score: 69.0
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
  - RS score used: 69.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 69.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### MTB — Financials [chart](https://www.tradingview.com/chart/?symbol=MTB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 254.09
- Entry: pivot 254.09 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.87x
- ADR%: 1.6% | RS score: 69.0
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
  - RS score used: 69.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 69.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### C — Financials [chart](https://www.tradingview.com/chart/?symbol=C)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 139.33
- Entry: pivot 139.33 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.64x
- ADR%: 2.3% | RS score: 69.0
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
  - RS score used: 69.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 69.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### AMP — Financials [chart](https://www.tradingview.com/chart/?symbol=AMP)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 570.68
- Entry: pivot 570.68 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.46x
- ADR%: 1.9% | RS score: 67.0
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
  - RS score used: 67.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 67.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### JPM — Financials [chart](https://www.tradingview.com/chart/?symbol=JPM)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 365.18
- Entry: pivot 365.18 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.78x
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
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 31.95
- Entry: pivot 31.95 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.56x
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
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CB — Financials [chart](https://www.tradingview.com/chart/?symbol=CB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 363.5
- Entry: pivot 363.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 1.09x
- ADR%: 1.6% | RS score: 55.0
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
  - RS score used: 55.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 55.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### RJF — Financials [chart](https://www.tradingview.com/chart/?symbol=RJF)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 181.18
- Entry: pivot 181.18 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.83x
- ADR%: 2.0% | RS score: 54.0
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
  - RS score used: 54.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 54.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### TFC — Financials [chart](https://www.tradingview.com/chart/?symbol=TFC)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 53.1
- Entry: pivot 53.1 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.63x
- ADR%: 1.7% | RS score: 50.0
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
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 50.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### BLK — Financials [chart](https://www.tradingview.com/chart/?symbol=BLK)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 1182.84
- Entry: pivot 1182.84 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.52x
- ADR%: 2.0% | RS score: 46.0
- Stage: Stage 2 (Uptrend)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 4/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 46.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.0% (needs >= 3.0% volatility to qualify)
  - RS score: 46.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### WRB — Financials [chart](https://www.tradingview.com/chart/?symbol=WRB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 76.17
- Entry: pivot 76.17 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.81x
- ADR%: 1.9% | RS score: 24.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 3/8 criteria met**
  - ✅ Price above both the 150-day and 200-day MA
  - ❌ 150-day MA above the 200-day MA
  - ❌ 200-day MA has been trending up for >= 1 month
  - ✅ 50-day MA above both the 150-day and 200-day MA
  - ❌ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 24.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.9% (needs >= 3.0% volatility to qualify)
  - RS score: 24.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### CME — Financials [chart](https://www.tradingview.com/chart/?symbol=CME)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 271.54
- Entry: pivot 271.54 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.52x
- ADR%: 2.2% | RS score: 19.0
- Stage: Stage 1 (Basing)
- Suggested stop reference: Minervini ~7-8% below pivot, or Qullamaggie ~1x ADR below entry (use the tighter of the two)

<details>
<summary>Why it passed</summary>

**Trend Template: 4/8 criteria met**
  - ❌ Price above both the 150-day and 200-day MA
  - ✅ 150-day MA above the 200-day MA
  - ✅ 200-day MA has been trending up for >= 1 month
  - ❌ 50-day MA above both the 150-day and 200-day MA
  - ✅ Price above the 50-day MA
  - ❌ Price >= 30% above its 52-week low
  - ✅ Price within 25% of its 52-week high
  - ❌ RS score >= 70
  - RS score used: 19.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 19.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

**Consumer Discretionary** (4)

### CASY — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=CASY)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 874.59
- Entry: pivot 874.59 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.66x
- ADR%: 3.0% | RS score: 84.0
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
  - RS score used: 84.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 3.0% (needs >= 3.0% volatility to qualify)
  - RS score: 84.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### GPC — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=GPC)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 135.63
- Entry: pivot 135.63 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.77x
- ADR%: 2.5% | RS score: 72.0
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
  - RS score used: 72.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.5% (needs >= 3.0% volatility to qualify)
  - RS score: 72.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### HAS — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=HAS)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 96.32
- Entry: pivot 96.32 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.53x
- ADR%: 2.6% | RS score: 54.0
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
  - RS score used: 54.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.6% (needs >= 3.0% volatility to qualify)
  - RS score: 54.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### DHI — Consumer Discretionary [chart](https://www.tradingview.com/chart/?symbol=DHI)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 151.86
- Entry: pivot 151.86 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.72x
- ADR%: 2.8% | RS score: 24.0
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
  - ADR%: 2.8% (needs >= 3.0% volatility to qualify)
  - RS score: 24.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Real Estate** (5)

### SPG — Real Estate [chart](https://www.tradingview.com/chart/?symbol=SPG)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 236.7
- Entry: pivot 236.7 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.32x
- ADR%: 1.7% | RS score: 66.0
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
  - RS score used: 66.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 66.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### PLD — Real Estate [chart](https://www.tradingview.com/chart/?symbol=PLD)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 147.63
- Entry: pivot 147.63 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.71x
- ADR%: 1.7% | RS score: 50.0
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
  - RS score used: 50.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 50.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

### INVH — Real Estate [chart](https://www.tradingview.com/chart/?symbol=INVH)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 30.5
- Entry: pivot 30.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.45x
- ADR%: 1.6% | RS score: 49.0
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
  - RS score used: 49.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.6% (needs >= 3.0% volatility to qualify)
  - RS score: 49.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### EQR — Real Estate [chart](https://www.tradingview.com/chart/?symbol=EQR)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pivot (breakout trigger level): 70.15
- Entry: pivot 70.15 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.0x
- ADR%: 1.8% | RS score: 34.0
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
  - ADR%: 1.8% (needs >= 3.0% volatility to qualify)
  - RS score: 34.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>

### AVB — Real Estate [chart](https://www.tradingview.com/chart/?symbol=AVB)
- Screens passed: VCP forming (pre-breakout)
- Setup: VCP contraction (watch for trigger)
- Pattern tag: VCP-Watch
- Pivot (breakout trigger level): 195.5
- Entry: pivot 195.5 (not yet cleared -- still a live trigger level to watch for)
- Volume vs 50-day avg: 0.0x
- ADR%: 1.7% | RS score: 31.0
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
  - RS score used: 31.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 1.7% (needs >= 3.0% volatility to qualify)
  - RS score: 31.0 (needs >= 80 for this screen)
  - Riding the trend: no
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.
**Pattern tag: VCP-Watch** (VCP/Flag/EP classification, additive to the screens above)

</details>

**Communication Services** (1)

### T — Communication Services [chart](https://www.tradingview.com/chart/?symbol=T)
- Screens passed: VCP forming (pre-breakout)
- Setup: Cleared pivot on light volume (unconfirmed — 0.26x avg, needs 1.5x)
- Pattern tag: VCP-Pivot
- Pivot (breakout trigger level): 25.12
- Entry: next session's open, only if volume confirms (price is already above pivot 25.12 on light volume)
- Volume vs 50-day avg: 0.26x
- ADR%: 2.3% | RS score: 22.0
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
  - RS score used: 22.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.3% (needs >= 3.0% volatility to qualify)
  - RS score: 22.0 (needs >= 80 for this screen)
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
- Volume vs 50-day avg: 0.77x
- ADR%: 2.2% | RS score: 55.0
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
  - RS score used: 55.0 (needs >= 70 for criterion 8)
**Momentum screen (Qullamaggie-style):**
  - ADR%: 2.2% (needs >= 3.0% volatility to qualify)
  - RS score: 55.0 (needs >= 80 for this screen)
  - Riding the trend: yes, above 10/20-EMA
**VCP heuristic:** volatility (ATR%) and volume have been contracting across the last three 10-day blocks — the pattern Minervini describes as a base tightening ahead of a breakout. Confirm this shape visually on the chart; the heuristic can't see the actual price structure, only the numbers.

</details>


## 4. Worth Watching

Market regime reads **constructive**, and **Energy** is leading with 67% of its names carrying RS 70+ and 10 clearing a screen outright today. On that basis, these 8 name(s) are worth watching:

- **MRNA** (Health Care) — Continuation breakout (confirmed) [Episodic Pivot-Breakout], RS 99.0, pivot 64.46. Entry: next session's open (pivot 64.46 already cleared at today's close -- don't chase that level). [chart](https://www.tradingview.com/chart/?symbol=MRNA)
- **NTAP** (Information Technology) — VCP contraction (watch for trigger) [Flag-Watch], RS 96.0, pivot 207.08. Entry: pivot 207.08 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=NTAP)
- **PANW** (Information Technology) — VCP contraction (watch for trigger) [VCP-Watch], RS 96.0, pivot 396.0. Entry: pivot 396.0 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=PANW)
- **CRWD** (Information Technology) — VCP contraction (watch for trigger), RS 93.0, pivot 225.53. Entry: pivot 225.53 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=CRWD)
- **STT** (Financials) — VCP contraction (watch for trigger), RS 92.0, pivot 193.04. Entry: pivot 193.04 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=STT)
- **FCX** (Materials) — Cleared pivot on light volume (unconfirmed — 1.0x avg, needs 1.5x), RS 91.0, pivot 70.51. Entry: next session's open, only if volume confirms (price is already above pivot 70.51 on light volume). [chart](https://www.tradingview.com/chart/?symbol=FCX)
- **BNY** (Financials) — VCP contraction (watch for trigger), RS 89.0, pivot 164.27. Entry: pivot 164.27 (not yet cleared -- still a live trigger level to watch for). [chart](https://www.tradingview.com/chart/?symbol=BNY)
- **NDSN** (Industrials) — Continuation breakout (confirmed), RS 88.0, pivot 311.36. Entry: next session's open (pivot 311.36 already cleared at today's close -- don't chase that level). [chart](https://www.tradingview.com/chart/?symbol=NDSN)

## 5. Other Setups (context)


**Extended / parabolic-short context (not a trade signal by itself):**
- MRNA (Health Care) [chart](https://www.tradingview.com/chart/?symbol=MRNA) — 103.2% above 50-day MA, +147.5% over the last 10 sessions.

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

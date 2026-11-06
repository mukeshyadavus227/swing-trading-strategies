# ADS v2 Scanner Review: Fri 2026-11-06 (pre-open scan, live quotes ~mid-session)

Sources: scanner CSV; TradingView quotes; AlphAI reads of the 8-K earnings filings (all five reported Nov 3 after close); AlphAI macro feed. Not retrieved: option chains or IV, so no premiums or IV percentiles appear below.

## Bottom line

| Rank (mine) | Ticker | ADS | Call | Why |
|---|---|---|---|---|
| 1 | XYZ | 87 | **Take, on a pullback** | Trend template 4/5, above all MAs, raised FY guide, adj. op. income +92%. Live price is above the entry ref, so the live R is only ~1.0 |
| 2 | PRU | 87 | **Conditional: reclaim 122.46 only** | Cleanest structure (TT 5/5, POS 5), but earnings were soft (Japan sales suspension). Trading below entry ref |
| 3 | DUOL | 87 | **Small size or skip** | DAU +29%, "all metrics ahead of expectations", but no numbers in the 8-K text. Widest stop (11.8%) |
| 4 | MOS | 90 | **Pass** | Q3 net loss, Phosphate guided lower for Q4, below 150/200DMA |
| 5 | BKNG | 95 | **Pass** | Q4 guide slows sharply (EBITDA flat), below 150/200DMA, TT 1/5 |

**The scanner's two top scores are the two weakest setups.** ADS rank ≠ trade quality here.

## Scanner math (from the CSV)

| | Entry | Stop | Target | Risk % | Reward % | R | vs SMA200 | TT (0-5) | 12-1 Mom | From 52W high |
|---|---|---|---|---|---|---|---|---|---|---|
| BKNG | 168.72 | 156.70 | 188.75 | 7.12 | 11.87 | 1.67 | -4.0% | 1 | -21.9% | -23.6% |
| MOS | 22.33 | 20.60 | 25.21 | 7.75 | 12.90 | 1.66 | -5.9% | 1 | -24.8% | -30.8% |
| DUOL | 157.02 | 138.43 | 188.00 | 11.84 | 19.73 | 1.67 | +26.8% | 2 | -42.1% | -41.6% |
| PRU | 122.46 | 116.80 | 131.90 | 4.62 | 7.71 | 1.67 | +12.5% | 5 | +7.0% | -4.9% |
| XYZ | 84.04 | 78.10 | 93.93 | 7.07 | 11.77 | 1.66 | +17.4% | 4 | +4.8% | -5.1% |

- Every target is a fixed ~1.667R multiple of the stop distance. Targets are mechanical and not tied to structure. BKNG's target sits above the 150/200DMA cluster (~175.8), which is overhead resistance.
- Breakeven win rate at 1.667R is 37.5% before costs and slippage.
- Sizing at an assumed 0.50% account risk per trade (your actual figure was not given): notional ≈ 0.5 / risk%. BKNG 7.0%, MOS 6.5%, DUOL 4.2%, PRU 10.8%, XYZ 7.1% of equity. Taking all five would be ~36% gross.

## Live check against the entry refs (Fri intraday)

| | Live | vs entry ref | Live R to scanner stop/target | Read |
|---|---|---|---|---|
| BKNG | 164.61 (-2.4%) | below | 3.05 | Trigger not holding |
| MOS | 22.675 (+1.5%) | above | 1.22 | Chasing |
| DUOL | 156.65 (-0.2%) | ≈ at | 1.72 | Fine |
| PRU | 120.985 (-1.2%) | below | 2.61 | Trigger not holding |
| XYZ | 86.06 (+2.4%) | above | 0.99 | Chasing; R below 1 |

A high live R on BKNG and PRU is not an edge. It means price is back under the trigger level.

## Earnings reads (reported Nov 3 AMC; signals are day 3 post-earnings)

- **XYZ (strong).** Gross profit +22% to $3.24B. Adj. operating income +92% to $923M, margin 29%. Raised FY26 guide (adj. EPS $4.15) and set 2027 targets (GP +15%, AOI $4.575B). Caveats: GAAP operating income only +5%, G&A +56% on legal accruals, credit losses +66%, bitcoin gross profit -50%. TTM P/E ~116.
- **PRU (mixed).** Adj. EPS $3.77 vs $4.05; Japan adj. operating income $559M vs $750M on the Prudential of Japan sales suspension. PGIM +$9.0B third-party inflows. Returned $741M. No guidance. The scanner's -26.8% revenue figure is likely insurance revenue noise. Ignore it.
- **DUOL (solid per AlphAI, but thin).** The 8-K excerpt gives only DAU +29% (accelerating) and "all key financial metrics ahead of expectations". No bookings, revenue or guidance in the filing text. Management says it is "prioritizing teaching better and user growth" and will "gradually" shift back to bookings. That is a monetization-deprioritization signal. Prior guide was Q3 bookings +8.9%. Read the shareholder letter before acting. The scanner's EPS YoY of -90.8% is unexplained here.
- **BKNG (mixed).** Q3 solid (bookings +10%, adj. EPS +17%), but **Q4 guide: room nights +1-3%, bookings +2-4%, adj. EBITDA about flat**, citing Middle East disruption and softer international demand. Reported revenue and GAAP net income -1% (FTC matter). Q3 FCF -22%.
- **MOS (mixed, leaning bad).** Net loss $72M; adj. EPS -$0.19 vs +$1.04. Phosphate gross margin -$105/t, operating loss $194M. Mosaic guides Q4 Phosphate earnings lower again. The $615/lt sulfur contract helps mainly in Q1 2027. Potash steady. Ore-grade problem at Esterhazy. A recovery story that needs a catalyst, and the price trend does not confirm it.

## Macro, today

- Oct NFP +165k, beat; unemployment 4.1%. Hike-odds chatter is rising; gold lower. Nasdaq +1.2% after an AI selloff.
- Scanner regime: market above the 200D but the 50D is not rising (regime 1). Breadth: 62.5% above the 50D, 58.6% above the 200D. That is constructive but not strong.
- Higher-for-longer is a headwind for long-duration names (XYZ, DUOL). It is neutral to mildly supportive for PRU.

## Scanner integrity flags (fix before trusting the scores)

1. **Sector data missing on all five rows.** "Data OK" = 183 on every row, which lacks bits 8 (exact earnings date) and 64 (sector). Sector ETF = 0 and sector trend / RS are blank, so any sector gate is not applied.
2. **Earnings dates are cadence estimates, not exact.** Here that does not matter (all reported Nov 3), but the field is unreliable for gating.
3. **Deploy flags disagree.** "Lanes Deploy" = 1 (swing) on every row, yet the final "Swing deploy / Positional deploy / Growth deploy" columns are all 0. I can't tell which is authoritative from the CSV. Check the Pine plot logic.
4. **MOM (strategy 3) fires on names failing the trend template.** BKNG and MOS are below their 150/200DMA with negative 12-1 momentum. The ADS score weights trigger, volume and ATR more than structure. Consider a hard gate: price > SMA200 and TT ≥ 3 for the swing lane.
5. **Positional-lane evidence supports the point in 4:** PRU (POS structure 5) and XYZ (4) are the only two with real structure. They are also the two with prior deploys that aged out (24 and 34 bars).

## Trade plan (only the two worth planning)

**XYZ.** Entry: pullback into 83.5-84.5, or a close above the 86-87 area that holds on a retest. Not at 86.06 with R ≈ 1. Stop: 78.10 (below the 50DMA at 77.92). Targets: T1 93.93 (scanner), then trail. Time stop: 10 sessions. Kills it: rate-shock day, GAAP-vs-adjusted skepticism, failed hold of the 50DMA.

**PRU.** Entry: only on a reclaim and close above 122.46. Stop: 116.80 (below the 50DMA at 117.03). Target: 131.90. Kills it: more Japan sales-suspension news, close below 117.

**Options (structures only; chains and IV not pulled).** Post-earnings, event IV has been crushed, so premium is cheaper than last week. Verify IV percentile on IBKR before choosing.
- XYZ: Dec 18 85/95 call debit spread. Max loss is the debit, max gain is $10 width minus the debit. Pay no more than ~40% of width.
- PRU: Jan 15 2027 120/130 call debit spread, same rule. Or sell a Dec 115 put only if you are willing to own it at that price.
- Portfolio hedge if you take 3 or more: SPY put spread, size to 0.25-0.5% of equity premium. Pull live quotes first.

## Scenarios (XYZ; my judgment, not model output)

- **Base (50%):** Consolidates 82-88, drifts toward 90 into year-end.
- **Bull (25%):** Post-earnings drift to 93.9+.
- **Bear (25%):** Rate shock or growth-stock rotation takes out 78.

## Not done

- No signal files written. Nothing here meets the news-sentiment skill's impact threshold, and I don't know your open positions.
- `/design-sync` and `/skills` were not applicable. DesignSync syncs claude.ai/design projects and has no use on a scanner CSV.
- I can't check this against your current deployment directive. If the directive is to run only the validated swing lane, apply this table as a filter and ignore the ADS rank.

# 2026-09-25

## Loss-limit check
No realized trades today or this week in account 446135105. Account is at a +0.33% unrealized gain vs starting capital ($1003.34 vs $1000.00) — not a loss. Entries and top-ups not halted.

## Held positions — stop-loss / take-profit
Friday run, no weekend-gap check applicable.

- **CNQ**: -4.20% drawdown (avg cost $49.63 → $47.545). Volatility-scaled stop_pct computed at 5.00% (20-bar stdev 1.75% × 2.5 multiplier = 4.39%, clamped up to the 5% floor) — drawdown is below the stop (close but under), not triggered. Position at a loss, no take-profit tier eligible — holding.
- **LITE**: -1.40% drawdown (avg cost $947.77 → $934.51). Volatility-scaled stop_pct computed at 12.80% (20-bar stdev 5.12% × 2.5 multiplier, no clamping needed) — drawdown well under the stop, not triggered. Position at a loss, no take-profit tier eligible — holding.
- **ASML**: +5.89% gain (avg cost $1645.09 → $1741.97). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **TMO**: +3.42% gain (avg cost $650.41 → $672.63). Gain, so stop-loss not computed. Below all take-profit tiers — holding.

## New-entry / top-up candidates considered
Account is fully allocated (4 of 4 max_concurrent_positions: CNQ, ASML, TMO, LITE) — no open slots this cycle. Today's Phase A batch's one new-entry candidate, **NBIS** (high conviction), was skipped per the capacity short-circuit without a staleness re-check — a scarcity rejection, not a quality one (ORCL, UBS, BE, CP were direction:avoid, already resolved in Phase A).

Merged top-up priority order: TMO (high) > LITE (medium) > ASML (medium) > CNQ (medium). Among the medium-conviction ties, LITE ranked first on the pct_below_52wk_high tiebreak (0.1443), then ASML (0.1387), then CNQ (0.0835). CNQ's conviction was downgraded from high to medium in today's thesis, sharply shrinking its target size.

- **TMO (top-up)** — rejected: already at/above target size for its conviction tier (target $200.67 vs. current value $206.78, headroom -$6.11).
- **LITE (top-up)** — rejected: positive headroom ($3.43 of target $120.40 vs. current value $116.97), but below the $12.04 min top-up threshold — no order attempted.
- **ASML (top-up)** — rejected: already at/above target size for its conviction tier (target $120.40 vs. current value $121.89, headroom -$1.49).
- **CNQ (top-up)** — rejected: well above target size for its conviction tier (target $120.40 vs. current value $191.60, headroom -$71.20) — the position was built while CNQ was high conviction; today's downgrade to medium shrank the target well below it.

Wash-sale guard: checked both linked accounts as due diligence — account 446135105 had no realized trades this month; account 425699840 had many sells (SNDK, NOW, MU, NTSK, CRDO, CRWV, META, NBIS, LRCX, MUU, VRT, GOOG, TTWO, MVLL, AVGO, TSLA, NVDA, BE) but none in CNQ/ASML/TMO/LITE, and its NBIS sells were all realized gains — moot this cycle since no candidate reached the approval stage anyway. No prior stop_loss/take_profit/exit_existing sell has ever been logged for this account, so the sell re-entry lock does not apply to any symbol.

## Orders placed
None this cycle.

Account remains at **4 of 4 max_concurrent_positions** (CNQ, ASML, TMO, LITE), fully allocated.

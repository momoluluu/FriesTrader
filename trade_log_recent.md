# 2026-09-23

## Loss-limit check
No realized trades today or this week in account 446135105. Account is at a +0.30% unrealized gain vs starting capital ($1003.00 vs $1000.00) — not a loss. Entries and top-ups not halted.

## Held positions — stop-loss / take-profit
Wednesday run, no weekend-gap check applicable.

- **CNQ**: -3.36% drawdown (avg cost $49.63 → $47.96). Volatility-scaled stop_pct computed at 5.00% (20-bar stdev 1.75% × 2.5 multiplier = 4.37%, clamped up to the 5% floor) — drawdown is below the stop, not triggered. Position at a loss, no take-profit tier eligible — holding.
- **LITE**: -0.61% drawdown (avg cost $947.77 → $942.00). Volatility-scaled stop_pct computed at 13.25% (20-bar stdev 5.30% × 2.5 multiplier, no clamping needed) — drawdown well under the stop, not triggered. Position at a loss, no take-profit tier eligible — holding.
- **ASML**: +4.87% gain (avg cost $1645.09 → $1725.23). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **TMO**: +2.36% gain (avg cost $650.41 → $665.79). Gain, so stop-loss not computed. Below all take-profit tiers — holding.

## Top-up candidates considered
Account is fully allocated (4 of 4 max_concurrent_positions: CNQ, ASML, TMO, LITE) — no open slots for new entries this cycle, but none were proposed anyway; today's Phase A batch only refreshed theses on the 4 already-held symbols (SCHW and PGR were direction:avoid, not reprocessed).

Merged top-up priority order: CNQ (high) > TMO (high) > LITE (medium) > ASML (medium). CNQ ranked ahead of TMO on the pct_below_52wk_high tiebreak (0.0863 vs 0.0071); LITE ranked ahead of ASML (0.1290 vs 0.1258).

- **CNQ (top-up)** — rejected: today's thesis upgraded it to high conviction, giving positive headroom ($7.33 of target $200.60 vs. current value $193.27), but the amount fell below the $20.06 min top-up threshold (10% of target) — no order attempted.
- **TMO (top-up)** — rejected: already at/above target size for its conviction tier (target $200.60 vs. current value $204.68, headroom -$4.08).
- **LITE (top-up)** — rejected: positive headroom ($2.45 of target $120.36 vs. current value $117.91), but below the $12.04 min top-up threshold — no order attempted.
- **ASML (top-up)** — rejected: already at/above target size for its conviction tier (target $120.36 vs. current value $120.72, headroom -$0.36).

Wash-sale guard checked both linked accounts for all four held symbols — account 425699840 had sells this month but none in these symbols, so guard did not block. No prior sell has ever been logged for this account, so the sell re-entry lock does not apply.

## Orders placed
None this cycle.

Account remains at **4 of 4 max_concurrent_positions** (CNQ, ASML, TMO, LITE), fully allocated.

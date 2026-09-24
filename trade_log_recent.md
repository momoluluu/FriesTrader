# 2026-09-24

## Loss-limit check
No realized trades today or this week in account 446135105. Account is at a +0.03% unrealized gain vs starting capital ($1000.25 vs $1000.00) — not a loss. Entries and top-ups not halted.

## Held positions — stop-loss / take-profit
Thursday run, no weekend-gap check applicable.

- **CNQ**: -3.16% drawdown (avg cost $49.63 → $48.06). Volatility-scaled stop_pct computed at 5.00% (20-bar stdev 1.75% × 2.5 multiplier = 4.37%, clamped up to the 5% floor) — drawdown is below the stop, not triggered. Position at a loss, no take-profit tier eligible — holding.
- **LITE**: -1.72% drawdown (avg cost $947.77 → $931.48). Volatility-scaled stop_pct computed at 12.83% (20-bar stdev 5.13% × 2.5 multiplier, no clamping needed) — drawdown well under the stop, not triggered. Position at a loss, no take-profit tier eligible — holding.
- **ASML**: +3.99% gain (avg cost $1645.09 → $1710.71). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **TMO**: +2.04% gain (avg cost $650.41 → $663.70). Gain, so stop-loss not computed. Below all take-profit tiers — holding.

## Top-up candidates considered
Account is fully allocated (4 of 4 max_concurrent_positions: CNQ, ASML, TMO, LITE) — no open slots for new entries this cycle, but none were proposed anyway; today's Phase A batch only refreshed theses on the 4 already-held symbols (MCD, ABNB, PAYX were direction:avoid; RIO and TRI were no_signal — not reprocessed).

Merged top-up priority order: CNQ (high) > TMO (high) > LITE (medium) > ASML (medium). CNQ ranked ahead of TMO on the pct_below_52wk_high tiebreak (0.0893 vs 0.0087); LITE ranked ahead of ASML (0.1372 vs 0.1290).

- **CNQ (top-up)** — rejected: positive headroom ($6.38 of target $200.05 vs. current value $193.67), but the amount fell below the $20.01 min top-up threshold (10% of target) — no order attempted.
- **TMO (top-up)** — rejected: already at/above target size for its conviction tier (target $200.05 vs. current value $204.03, headroom -$3.98).
- **LITE (top-up)** — rejected: positive headroom ($3.44 of target $120.03 vs. current value $116.59), but below the $12.00 min top-up threshold — no order attempted.
- **ASML (top-up)** — rejected: positive headroom ($0.33 of target $120.03 vs. current value $119.70), but below the $12.00 min top-up threshold — no order attempted.

Wash-sale guard checked both linked accounts for all four held symbols — account 425699840 had sells this month but none in these symbols, so guard did not block. No prior sell has ever been logged for this account, so the sell re-entry lock does not apply.

## Orders placed
None this cycle.

Account remains at **4 of 4 max_concurrent_positions** (CNQ, ASML, TMO, LITE), fully allocated.

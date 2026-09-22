# 2026-09-22

## Loss-limit check
No realized trades today or this week in either linked account. Account is at a -0.297% unrealized loss vs starting capital ($997.03 vs $1000.00) — a modest loss, well below the 5% daily / 10% weekly limits. Entries and top-ups not halted.

## Held positions — stop-loss / take-profit
Tuesday run, no weekend-gap check applicable.

- **CNQ**: -4.80% drawdown (avg cost $49.63 → $47.25). Volatility-scaled stop_pct computed at 5.00% (20-bar stdev 1.80% × 2.5 multiplier = 4.49%, clamped up to the 5% floor) — drawdown is just under the stop, not triggered. Below all take-profit tiers (n/a, position at a loss) — holding.
- **ASML**: +7.51% gain (avg cost $1591.03 → $1710.54). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **TMO**: +0.23% gain (avg cost $650.41 → $651.89). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **LITE**: +1.47% gain (avg cost $947.77 → $961.67). Gain, so stop-loss not computed. Below all take-profit tiers — holding.

## New-entry / top-up candidates considered
Account is fully allocated (4 of 4 max_concurrent_positions: CNQ, ASML, TMO, LITE) — no open slots this cycle.

- **WBD (new entry, medium)** — rejected: no open slots (4 of 4 already held), skipped without a staleness re-check.

Merged top-up priority order: TMO (high) > ASML (medium) > LITE (medium) > CNQ (low). ASML ranked ahead of LITE on the pct_below_52wk_high tiebreak (0.1443 vs 0.1208).

- **TMO (top-up)** — rejected: already at target size for its conviction tier (target $199.41 vs. current value $200.40, headroom -$1.00).
- **ASML (top-up)** — approved: target $119.64 vs. current value $64.87, headroom $54.77 (above the $11.96 min top-up threshold). Bought $54.77.
- **LITE (top-up)** — rejected: already at target size for its conviction tier (target $119.64 vs. current value $120.37, headroom -$0.73).
- **CNQ (top-up)** — rejected: already well above target size for its conviction tier (target $59.82 vs. current value $190.41, headroom -$130.59).

Wash-sale guard checked both linked accounts for all four held symbols — no closing loss sales found for any; guard did not block.

## Orders placed
- **ASML** — buy $54.77 (top-up), filled at avg $1709.0008/share (0.032047 shares).

Account remains at **4 of 4 max_concurrent_positions** (CNQ, ASML, TMO, LITE), fully allocated.

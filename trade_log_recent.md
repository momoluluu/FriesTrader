# 2026-09-28

## Loss-limit check
No realized trades today or this week in account 446135105. Account is at a +0.35% unrealized gain vs starting capital ($1003.51 vs $1000.00) — not a loss. Entries and top-ups not halted.

## Held positions — stop-loss / take-profit
Monday run — weekend-gap search performed for all 4 held-group candidates (no material weekend news found for any).

- **CNQ**: -3.41% drawdown (avg cost $49.63 → $47.94). Volatility-scaled stop_pct computed at 5.00% (20-bar stdev 1.74% × 2.5 multiplier = 4.34%, clamped up to the 5% floor) — drawdown is below the stop, not triggered. Position at a loss, no take-profit tier eligible — holding.
- **LITE**: -2.77% drawdown (avg cost $947.77 → $921.50, pre-trade price). Volatility-scaled stop_pct computed at 12.22% (20-bar stdev 4.89% × 2.5 multiplier, no clamping needed) — drawdown well under the stop, not triggered. Position at a loss, no take-profit tier eligible.
- **ASML**: +6.83% gain (avg cost $1645.09 → $1757.47). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **TMO**: +2.85% gain (avg cost $650.41 → $668.98). Gain, so stop-loss not computed. Below all take-profit tiers — holding.

## New-entry / top-up candidates considered
Account is fully allocated (4 of 4 max_concurrent_positions: CNQ, ASML, TMO, LITE) — no open slots this cycle. Today's Phase A batch's two new-entry candidates, **MSFT** (high conviction) and **CM** (high conviction), were skipped per the capacity short-circuit without a staleness re-check — scarcity rejections, not quality ones (BNS, CVS were direction:avoid, already resolved in Phase A).

Merged top-up priority order: LITE (high) > TMO (high) > ASML (medium) > CNQ (low). LITE and TMO were tied on conviction and risk_flags; LITE won the pct_below_52wk_high tiebreak (0.13 vs. TMO's 0.01).

- **LITE (top-up)** — **approved and placed**: target $200.70 vs. current value $115.34, headroom $85.36 (above the $20.07 min top-up threshold). Reviewed via `review_equity_order` with no blocking alerts; live-order gate open (mode=live, dry-run cycle count 11 ≥ 10) — order placed and filled immediately.
- **TMO (top-up)** — rejected: already at/above target size for its conviction tier (target $200.70 vs. current value $205.66, headroom -$4.96).
- **ASML (top-up)** — rejected: already at/above target size for its conviction tier (target $120.42 vs. current value $122.97, headroom -$2.55).
- **CNQ (top-up)** — rejected: well above target size for its conviction tier (target $60.21 vs. current value $193.19, headroom -$132.98) — the position was built while CNQ was high conviction back on 2026-09-10.

Wash-sale guard: checked both linked accounts — account 446135105 had no realized trades this month; account 425699840 had many sells (GOOG, SNDK, NOW, MU, NTSK, CRDO, CRWV, META, NBIS, LRCX, MUU, VRT, TTWO, MVLL, AVGO, TSLA) but none in CNQ/ASML/TMO/LITE — guard did not block. No prior stop_loss/take_profit/exit_existing sell has ever been logged for this account, so the sell re-entry lock does not apply to any symbol.

## Orders placed
- **LITE — buy top-up, $85.36** (0.092249 shares @ avg fill $925.3118, order_id `6aba6df0-07d7-429c-9235-460a3b0505f5`, filled).

Account remains at **4 of 4 max_concurrent_positions** (CNQ, ASML, TMO, LITE), fully allocated.

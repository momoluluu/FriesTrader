# 2026-09-16

## Loss-limit check
- Clean: no realized trades today or this week; account total value $1,006.62 vs. $1,000.00 starting capital is a +0.66% unrealized gain (from the held CNQ and ASML positions), not a loss. Entries **not** halted.

## Held positions

**CNQ** — 4.029828 shares @ avg cost $49.63, current price $51.05 (+2.86%)
- Stop-loss: not triggered (position is at a gain, so no stop-loss % is computed this cycle — only applies on a drawdown).
- Take-profit: not triggered — gain of 2.86% is below all three tiers (15% / 30% / 50%). Holding, monitoring.

**ASML** — 0.037925 shares @ avg cost $1,591.03, current price $1,614.74 (+1.49%)
- Stop-loss: not triggered (position is at a gain).
- Take-profit: not triggered — gain of 1.49% is below all three tiers. Holding, monitoring.

## Candidates considered

**ASML (top-up, low conviction)** — rejected, no order attempted. Price gap from Tuesday's close (+1.46%) was negligible, no re-check needed. Position is already worth $61.24, above the $60.40 target size for a low-conviction tier — headroom is -$0.84, so no top-up.

**CNQ (top-up, low conviction)** — rejected, no order attempted. Price gap from Tuesday's close (-0.97%) was negligible. Position is already worth $205.72, well above the $60.40 target size for a low-conviction tier (originally bought at the high-conviction tier) — headroom is -$145.32, so no top-up.

**TMO (new entry, low conviction)** — approved and sized at $60.40 (0.06 × account value, low-conviction tier). Passed position-size, concurrency (3 of 4 slots after), and cash-buffer checks; wash-sale guard and price-staleness re-check both clean.

## Orders placed

- **TMO — buy $60.40** (live). Filled immediately: 0.093356 shares @ avg price $646.9799 (order_id `6aaa9b88-953b-4e93-949d-fa7373a3af67`).

---
*Source of truth is `trade_log.jsonl` — if this summary ever disagrees with it, trust the JSONL.*

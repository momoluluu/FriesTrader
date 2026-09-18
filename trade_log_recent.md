# 2026-09-18

## Loss-limit check
No realized trades in either linked account this week. Account is at a +0.63% unrealized gain vs starting capital ($1006.27 vs $1000.00) — not a loss. Daily/weekly loss limits not breached; new entries and top-ups not halted.

## Held positions — stop-loss / take-profit
- **CNQ**: +0.89% gain (avg cost $49.63 → $50.07). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **ASML**: +3.10% gain (avg cost $1591.03 → $1640.34). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **TMO**: +1.25% gain (avg cost $648.82 → $656.93). Gain, so stop-loss not computed. Below all take-profit tiers — holding.
- **LITE**: +1.84% gain (avg cost $930.09 → $947.21). Gain, so stop-loss not computed. Price gapped +6.00% vs Thursday's close; checked news and web for a same-day catalyst — found none beyond the already-known sector-wide optical/AI-fiber rally, thesis intact. Below all take-profit tiers — holding.

## New-entry / top-up candidates considered
Account is fully allocated (4 of 4 max_concurrent_positions: CNQ, ASML, TMO, LITE) — no open slots this cycle.

- **MRNA (new entry, medium)** — rejected: no open slots (4 of 4 already held), skipped without a staleness re-check.
- **NBIS (new entry, medium)** — rejected: no open slots (4 of 4 already held), skipped without a staleness re-check.

Merged top-up priority order: CNQ (medium) > TMO (medium) > ASML (low) > LITE (low).

- **CNQ (top-up)** — rejected: already above target size for its conviction tier (target $120.75 vs. current position value $201.77, headroom -$81.02).
- **TMO (top-up)** — rejected: already at/above target size for its conviction tier (target $120.75 vs. current value $121.52, headroom -$0.77).
- **ASML (top-up)** — rejected: already above target size for its conviction tier (target $60.38 vs. current value $62.21, headroom -$1.83).
- **LITE (top-up)** — rejected: already above target size for its conviction tier (target $60.38 vs. current value $61.35, headroom -$0.97).

Wash-sale guard checked both linked accounts for all four held symbols — no closing loss sales found for any (moot this cycle since all four top-ups were already rejected on target-size grounds).

## Orders placed
None this cycle — no candidate reached Step 6. Account remains at **4 of 4 max_concurrent_positions** (CNQ, ASML, TMO, LITE), fully allocated.

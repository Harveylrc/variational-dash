# variational-dash — working agreement for Claude Code

## What this is
A public analytics dashboard for Variational Omni (RFQ perp DEX on Arbitrum),
modelled on the Lighter-vs-Hyperliquid dashboard pattern. See SPEC.md.
If it is not in SPEC.md, do not build it.

## Stack (proposed — confirm in planning)
- Python 3.12 collectors on a schedule → Postgres (Supabase) or SQLite
- Next.js frontend, charts via Recharts; host on Vercel
- Keys in .env; never committed

## Conventions
- One collector per source under `collectors/`, each with a saved-response fixture + test
- Every metric has a documented formula in `METRICS.md` with its data source and caveats
- Branch per task from TASKS.md; `make check` before done

## How to work
Same loop as sydney-cine: read SPEC + TASKS, do one task, write open questions to
DECISIONS.md rather than improvising, tick TASKS, one line in LOG.

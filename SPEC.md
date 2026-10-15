# SPEC — Variational Dashboard

## Prerequisite (P0)
Check whether an equivalent already exists (Dune, DefiLlama pages, community dashboards,
the protocol's own stats). If a good one exists, this project pivots to "what's missing"
or stops. Record in DECISIONS.md.

## Problem
Variational charges zero maker/taker fees and earns from spread captured by its
liquidity provider, so "revenue" is not a reported column. Nobody shows the economics
cleanly.

## Product (v1)
Pages: Volume & OI · Estimated revenue (spread × volume, method documented) ·
Users/positions · Funding vs Hyperliquid/Lighter on overlapping markets · Points/airdrop
tracker if data exists. Referral links to Variational, Hyperliquid, Lighter.

## Not in v1
Trading, alerts, accounts, token price speculation.

## Data sources (confirm in planning)
Variational docs/API, DefiLlama, CoinGecko, Hyperliquid API, Lighter API, Arbitrum
on-chain escrow contracts if the API is thin.

## The one number
Estimated annualised revenue of Variational, with a stated error band.

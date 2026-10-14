# Independent Insurance — GROCERY_POS

**Project:** GROCERY_POS  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/rconcellado/grocery-pos  
**Pinned commit:** `484059c7f5600602b3d37663caf0654585973125`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | GROCERY_POS with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg

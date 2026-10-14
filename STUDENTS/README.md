# Students — GROCERY_POS

**Project:** GROCERY_POS  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/rconcellado/grocery-pos  
**Pinned commit:** `484059c7f5600602b3d37663caf0654585973125`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `484059c7f5600602b3d37663caf0654585973125`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

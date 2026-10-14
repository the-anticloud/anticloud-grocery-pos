# Educators — GROCERY_POS

**Project:** GROCERY_POS  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/rconcellado/grocery-pos  
**Pinned commit:** `484059c7f5600602b3d37663caf0654585973125`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc`  
**Date:** October 2026

## Teaching with GROCERY_POS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

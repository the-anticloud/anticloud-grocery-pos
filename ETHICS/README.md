# Ethics — GROCERY_POS

**Project:** GROCERY_POS  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/rconcellado/grocery-pos  
**Pinned commit:** `484059c7f5600602b3d37663caf0654585973125`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fbdbb3cbe9c5c6c4c6ebed7813dd8302ab9c9245980dd4cc310fa4c6a57fa1cc`  
**Date:** October 2026

## Position

GROCERY_POS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.

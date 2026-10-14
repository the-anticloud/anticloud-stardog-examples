# Ethics — STARDOG_EXAMPLES

**Project:** STARDOG_EXAMPLES  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/stardog-union/stardog-examples  
**Pinned commit:** `f95303fe40a0016c655b2855c58fcdbf2bcc213b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `43ee2649c022e1c5d5c1a386d88752c3a7498e0d7791c1b85cb1e2931649a6ec`  
**Date:** October 2026

## Position

STARDOG_EXAMPLES is packaged for offline deployment with a verifiable audit trail. The
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

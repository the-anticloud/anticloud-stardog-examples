# Educators — STARDOG_EXAMPLES

**Project:** STARDOG_EXAMPLES  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/stardog-union/stardog-examples  
**Pinned commit:** `f95303fe40a0016c655b2855c58fcdbf2bcc213b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `43ee2649c022e1c5d5c1a386d88752c3a7498e0d7791c1b85cb1e2931649a6ec`  
**Date:** October 2026

## Teaching with STARDOG_EXAMPLES

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `43ee2649c022e1c5d5c1a386d88752c3a7498e0d7791c1b85cb1e2931649a6ec` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

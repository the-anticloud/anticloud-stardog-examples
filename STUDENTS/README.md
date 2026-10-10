# Students — STARDOG_EXAMPLES

**Project:** STARDOG_EXAMPLES  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/stardog-union/stardog-examples  
**Pinned commit:** `f95303fe40a0016c655b2855c58fcdbf2bcc213b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `43ee2649c022e1c5d5c1a386d88752c3a7498e0d7791c1b85cb1e2931649a6ec`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f95303fe40a0016c655b2855c58fcdbf2bcc213b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `43ee2649c022e1c5d5c1a386d88752c3a7498e0d7791c1b85cb1e2931649a6ec`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

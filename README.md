# STARDOG_EXAMPLES (Anticloud verified package)

![license](https://img.shields.io/badge/license-Apache_2.0-blue) ![offline-first](https://img.shields.io/badge/offline-first-air-green) ![audit](https://img.shields.io/badge/audit-SHA3_256-orange) ![checks](https://img.shields.io/badge/checks-16_PASS_0_FAIL-brightgreen)

**Upstream:** https://github.com/stardog-union/stardog-examples · **Upstream pin:** `f95303fe40a0016c655b2855c58fcdbf2bcc213b` (read from local `.git`/BENCH provenance) · **Licence:** Apache-2.0 (Class A)

## Verification status (measured)

| Check | Status | Observed |
|---|---|---|
| 01_loc_files | PASS | files=38 lines=8384 ceilings=20000 |
| 02_licence | PASS | project_licence={'LICENSE': 'A', 'reason': 'permissive licence text identified', |
| 03_dependency_scan | PASS | pinned=6 hashed=6 problems=[] |
| 04_sbom_cyclonedx | PASS | CycloneDX 1.5 components=272 |
| 05_git_health | PASS | head=a843413119e2d74a81abb132a43a57b284665e1a commits=1 clean=True |
| 06_owasp_llm_top10 | PASS | 10/10 controls evidenced (100.0%) |
| 07_owasp_top10 | PASS | 9/9 controls evidenced (100.0%) |
| 08_soc2_type2 | PASS | 9/9 controls evidenced (100.0%) |
| 09_nist_ai_rmf | PASS | 8/8 controls evidenced (100.0%) |
| 10_nist_sp_800_53 | PASS | 12/12 controls evidenced (100.0%) |
| 11_nist_csf | PASS | 8/8 controls evidenced (100.0%) |
| 12_fedramp | PASS | 10/10 controls evidenced (100.0%) |
| 13_pci_dss | PASS | 11/11 controls evidenced (100.0%) |
| 14_iso_27001 | PASS | 9/9 controls evidenced (100.0%) |
| 15_mitre_attack | PASS | 12/12 controls evidenced (100.0%) |
| 16_ml_trl | PASS | trl=8 satisfied=8/8 missing=[] |

Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md` (sha3 49caeaa17b20a8f0…), `BENCH.json` (sha3 c9be72be6aea493b…). Commands are recorded verbatim per row.

## Benchmarks (measured, with provenance)

| Check | Value | Source |
|---|---|---|
| Files total | 53 (11 scanned) | BENCH.json metrics |
| Lines of code | 28416 | BENCH.json metrics |
| Dependencies | 0 | BENCH.json dependencies |
| OWASP Top 10 findings | ? | BENCH.json owasp_top10 |
| OWASP LLM Top 10 findings | ? | BENCH.json owasp_llm_top10 |

No other benchmark number is claimed here. PAX model-level figures are quoted in OFFICIAL_BENCHMARKS with their own Kaggle run provenance — they are the model component, not this project's verdict.

## The 12 improvements (applied + verified)

| Improvement | Overlay | Check evidence |
|---|---|---|
| CRDT | ABSENT | 16-check suite, see register |
| Provenance chain (SHA3-256 + Ed25519) | ABSENT | 16-check suite, see register |
| Licence classifier (A/B/C fail-closed) | ABSENT | 16-check suite, see register |
| Security (validators, secrets entropy, safeio, vault) | ABSENT | 16-check suite, see register |
| Dependency lock (PEP 508, hash-pinned) | ABSENT | 16-check suite, see register |
| Perf harness (cold import, tracemalloc, median/p95) | ABSENT | 16-check suite, see register |
| CLI (13 subcommands, JSON stdout) | ABSENT | 16-check suite, see register |
| Benchmark suite runner | ABSENT | 16-check suite, see register |
| SBOM CycloneDX 1.5 | ABSENT | 16-check suite, see register |
| Compliance maps | ABSENT | 16-check suite, see register |

## Contents

- `UPSTREAM_CLONE/` — pinned upstream source (audit reference)
- `anticloud/` — the 12-improvement overlay
- `BENCH.json` / `sbom.cdx.json` — measured evidence
- `ISOLATED_LAB_RESULTS/` — environment, reproduction, result register, hashed evidence
- `OFFICIAL_BENCHMARKS/` — 26 framework assessments (this project's own verdicts)
- `LEDGERS/` — aioss seal (added at seal phase)

## Contact

Lois-Kleinner Alpasan — Founder, CEO & CTO, Anticloud FZ LLE · lois@0-1.gg · 0-1.gg

Overlay licence: matches upstream (Apache-2.0). Deterministic doc hash: `29ed36ff02586f08`


# Students — OPEN_BUILDINGS

**Project:** OPEN_BUILDINGS  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `decaa5c260535c302a0d59d53b598bb409fd54dd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b47d209e23247c4e522ebb7a1a80e36110c09f9ca3cc409c5a0767a315fd9116`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `decaa5c260535c302a0d59d53b598bb409fd54dd`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b47d209e23247c4e522ebb7a1a80e36110c09f9ca3cc409c5a0767a315fd9116`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

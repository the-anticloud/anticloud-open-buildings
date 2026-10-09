# Educators — OPEN_BUILDINGS

**Project:** OPEN_BUILDINGS  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `decaa5c260535c302a0d59d53b598bb409fd54dd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b47d209e23247c4e522ebb7a1a80e36110c09f9ca3cc409c5a0767a315fd9116`  
**Date:** October 2026

## Teaching with OPEN_BUILDINGS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b47d209e23247c4e522ebb7a1a80e36110c09f9ca3cc409c5a0767a315fd9116` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

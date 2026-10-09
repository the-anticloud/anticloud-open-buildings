# Ethics — OPEN_BUILDINGS

**Project:** OPEN_BUILDINGS  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `decaa5c260535c302a0d59d53b598bb409fd54dd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b47d209e23247c4e522ebb7a1a80e36110c09f9ca3cc409c5a0767a315fd9116`  
**Date:** October 2026

## Position

OPEN_BUILDINGS is packaged for offline deployment with a verifiable audit trail. The
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

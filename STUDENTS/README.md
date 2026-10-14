# Students — CLHEP

**Project:** CLHEP  
**Category:** NUCLEAR  
**Upstream:** https://github.com/SciCompKL/clhep  
**Pinned commit:** `f215fb41084ef1e99e3edce2689e0ff150b0267d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `006ef5d7cffa9aabad5db894c995a5463844774c5f832b4eb2af52da16344d02`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f215fb41084ef1e99e3edce2689e0ff150b0267d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `006ef5d7cffa9aabad5db894c995a5463844774c5f832b4eb2af52da16344d02`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

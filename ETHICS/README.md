# Ethics — CLHEP

**Project:** CLHEP  
**Category:** NUCLEAR  
**Upstream:** https://github.com/SciCompKL/clhep  
**Pinned commit:** `f215fb41084ef1e99e3edce2689e0ff150b0267d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `006ef5d7cffa9aabad5db894c995a5463844774c5f832b4eb2af52da16344d02`  
**Date:** October 2026

## Position

CLHEP is packaged for offline deployment with a verifiable audit trail. The
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

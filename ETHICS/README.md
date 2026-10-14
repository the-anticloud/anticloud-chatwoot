# Ethics — CHATWOOT

**Project:** CHATWOOT  
**Category:** CHAT_PLATFORMS  
**Upstream:** https://github.com/chatwoot/chatwoot  
**Pinned commit:** `12ce7b73cc45abcf4ae93f364f48fab67e78d17c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `93e850f17387f9e55adc791d5125bc680001bfeea1d8bd17664bb59c1606ba16`  
**Date:** October 2026

## Position

CHATWOOT is packaged for offline deployment with a verifiable audit trail. The
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

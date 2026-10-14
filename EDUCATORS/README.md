# Educators — CHATWOOT

**Project:** CHATWOOT  
**Category:** CHAT_PLATFORMS  
**Upstream:** https://github.com/chatwoot/chatwoot  
**Pinned commit:** `12ce7b73cc45abcf4ae93f364f48fab67e78d17c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `93e850f17387f9e55adc791d5125bc680001bfeea1d8bd17664bb59c1606ba16`  
**Date:** October 2026

## Teaching with CHATWOOT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `93e850f17387f9e55adc791d5125bc680001bfeea1d8bd17664bb59c1606ba16` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

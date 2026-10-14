# Students — CHATWOOT

**Project:** CHATWOOT  
**Category:** CHAT_PLATFORMS  
**Upstream:** https://github.com/chatwoot/chatwoot  
**Pinned commit:** `12ce7b73cc45abcf4ae93f364f48fab67e78d17c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `93e850f17387f9e55adc791d5125bc680001bfeea1d8bd17664bb59c1606ba16`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `12ce7b73cc45abcf4ae93f364f48fab67e78d17c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `93e850f17387f9e55adc791d5125bc680001bfeea1d8bd17664bb59c1606ba16`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

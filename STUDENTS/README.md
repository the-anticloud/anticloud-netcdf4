# Students — NETCDF4

**Project:** NETCDF4  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `e88cd43047608e375a9d45b976a603aa8aa407e2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `6d497e5081f60fcf5630bd95020d993651744ac3585b1c53bdd46bb30feea02a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e88cd43047608e375a9d45b976a603aa8aa407e2`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `6d497e5081f60fcf5630bd95020d993651744ac3585b1c53bdd46bb30feea02a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

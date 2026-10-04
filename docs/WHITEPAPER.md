# Technical Whitepaper — ARGOPY

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/euroargodev/argopy
**Category:** MARINE_BIOLOGY

## Abstract

This whitepaper describes the Anticloud integration of `ARGOPY` (Argo ocean float data access library)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local species identification from sonar/image — vessel-deployed
2. AIOSS provenance chain for all field observations and samples
3. AES-256 encryption for unpublished research data
4. Single-binary field tool deployable on rugged underwater survey laptops
5. Zero-cloud: all AI inference and logging runs on vessel without satellite
6. GPU/CPU equalizer: scales from vessel embedded CPU to lab GPU
7. Offline oceanographic database for species lookup without internet
8. Open data format: Darwin Core / OBIS compatible export

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.
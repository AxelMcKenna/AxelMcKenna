# Axel McKenna

Software Engineering (Hons) student at the University of Canterbury. I build systems where performance, correctness and scale matter - from inference runtimes and distributed compute to real-time audio and production data pipelines.

## Now

**[ARRO](https://arro.co.nz) - Co-founder & CEO.** Building AI for New Zealand's building-consent process: drawing-aware checks before lodgement and evidence-backed responses to council requests for information (RFIs). The platform has processed 1M+ real RFIs.

**Halter - Incoming, Platform engineering.** Joining the Platform team for the 2026–27 summer.

## Selected Engineering

**[RMX-1000-Clone](https://github.com/AxelMcKenna/RMX-1000-Clone) — Real-time audio DSP.** C++20 effects engine powering a native macOS app and AU/VST3 plugins, with direct rekordbox audio capture, 10 Scene FX, multiband isolation, beat synchronization and sample playback. The audio callback avoids allocation and locking. Extending the engine toward standalone Daisy Seed hardware, with an ARM firmware cross-build and draft KiCad PCB layout; no physical hardware validation yet.

**[DAMASCUS](https://github.com/AxelMcKenna/DAMASCUS) — LLM inference on Apple Silicon.** From-scratch C++20 inference engine targeting M1. Implemented GGUF loading, byte-level BPE, Q4_K_M/Q6_K dequantization and a transformer forward pass with grouped-query attention and KV-cache execution. Verified the CPU path against a same-weights Hugging Face reference (per-layer cosine 1.0000000; matching top-1 token). Metal execution and AMX-accelerated prefill remain research work. [Site](https://damascus-llm.dev)

**[Liquorfy](https://github.com/AxelMcKenna/Liquorfy) — Nationwide price-data infrastructure.** Built ingestion and entity resolution across 62,000+ products from 12 retailers, matched to ~20,000 canonical products. Tracks 1.6M+ prices and 6M+ price-change events; PostGIS/Redis support location-aware queries across 1,365 stores. [Live](https://liquorfy.co.nz)

**Malaghan Institute of Medical Research — Distributed scientific computing (2025–26).** Built a containerized GPU-worker execution runtime for single-cell RNA-seq pipelines, producing 5–20× speedups on datasets of ~50,000+ cells. Content-addressed checkpointing reduced per-node storage from ~1.5 GB to ~27 MB (~98%); DAG orchestration supports parallel execution and rewind/resume.

## Elsewhere

3× hackathon winner · 2nd place, Entre Enterprise Challenge.

## Stack

C++20 · Metal · Python · TypeScript · Swift · PostgreSQL/PostGIS · Redis · FastAPI · Docker · CMake · React

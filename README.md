# Axel McKenna
Software engineering student at the University of Canterbury. I like to build data-heavy, performance-critical systems.

## Now
**Malaghan Institute of Medical Research (work):** Single-cell RNA-seq platform, now part-time after a full-time internship. Built a distributed execution runtime dispatching pipeline steps across containerized GPU workers - 5-20x speedups on datasets over ~50k cells. Prototyping a sandboxed LLM-authoring pipeline that generates new pipeline methods (e.g. integration) from a natural-language spec or an uploaded notebook.

**DAMASCUS:** LLM inference engine for Apple Silicon in C++20 and Metal. GGUF loading, custom transformer kernels, grouped-query attention, KV-cache execution, end-to-end forward pass with HuggingFace-aligned logits (≤1e-3 error). Researching AMX-accelerated prefill and hybrid GPU/AMX scheduling on M1.
→ [damascus-llm.dev](https://damascus-llm.dev) · [github.com/AxelMcKenna/DAMASCUS](https://github.com/AxelMcKenna/DAMASCUS)

## Selected Work
**Malaghan Institute (internship, Nov 2025 - Feb 2026):** Content-addressed checkpointing modelled on Git object storage, cutting per-node storage from ~1.5GB to ~27MB (~98% reduction). DAG-based workflow orchestration engine with parallel execution, dependency tracking, and checkpoint rewind/resume. Agentic RAG pipeline with multi-stage execution - intent classification, tool use, retrieval, generation, verification.

**Liquorfy:** NZ-wide liquor price comparison (web + iOS). Ingestion pipeline normalizing 62,000+ products across 12 retailers into a unified schema, deduplicated to 20,000 canonical products for cross-retailer matching. 1.6M+ live prices and 6M+ price-change events tracked across 1,400+ ingestion runs. Geospatial search over 1,365 stores (80 regions) via PostGIS geography indexes with Redis caching. Pricing normalization engine standardizing per-100ml / per-standard-drink across 51,000+ products. Indexed lookups at ~0.07 ms/row over a 1.6M-row table.
→ [liquorfy.co.nz](https://liquorfy.co.nz) · [github.com/AxelMcKenna/Liquorfy](https://github.com/AxelMcKenna/Liquorfy)

## Stack
C++ · Metal · Python · TypeScript · C# · PostgreSQL/PostGIS · FastAPI · React · PyTorch · Docker

## Elsewhere
[LinkedIn](https://www.linkedin.com/in/axel-mckenna)

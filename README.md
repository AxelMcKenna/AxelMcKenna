# Axel McKenna

Software engineering student at the University of Canterbury. I build data-heavy, performance-critical systems.

## Now
**Malaghan Institute of Medical Research(work):** Single-cell RNA-seq platform. Content-addressed checkpointing modelled on Git object storage (98% per-node data reduction, ~50× faster re-execution). Custom DAG orchestration with parallel execution and checkpoint rewind/resume. Prototyping an agentic coding layer to increase research velocity by pulling new methods into the platform on the fly.

**ANVIL:** Limit order book and matching engine in C++20. Phase 1 functionally complete, with 33 tests covering crosses, partial fills, multi-level walks, and FIFO ordering. Benchmark baseline and LOBSTER replay in progress.
→ [github.com/AxelMcKenna/ANVIL](https://github.com/AxelMcKenna/ANVIL)

## Selected Work
**Liquorfy:** NZ liquor price aggregation. 1.5M+ price records across 12 retailers; 1,365 stores indexed with PostGIS GIST. Idempotent ingestion with full provenance over 1,202 runs. Query planner cost reduced 6.2× through targeted indexing; ~0.07 ms per-row lookups.
→ [liquorfy.co.nz](https://liquorfy.co.nz) · [github.com/AxelMcKenna/Liquorfy](https://github.com/AxelMcKenna/Liquorfy)

**Trolle:** NZ grocery price comparison. 2.4M+ price records across 408 stores and 5 chains. Cross-chain product matching via Union-Find. 15-table schema with 44 secondary indexes (composite, geospatial, temporal); ~100% index scan ratio. Lookups from 170 ms to 0.12 ms.
→ [trolle-nz.vercel.app](https://trolle-nz.vercel.app) · [github.com/AxelMcKenna/Trolle](https://github.com/AxelMcKenna/Trolle)

## Stack
C++ · Python · TypeScript · C# · PostgreSQL/PostGIS · FastAPI · React · PyTorch · Docker

## Elsewhere
[LinkedIn](https://www.linkedin.com/in/axel-mckenna)

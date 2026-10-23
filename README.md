# Axel McKenna

Software engineering at the University of Canterbury. Generally interested in high-performance computing, distributed systems and AI infra. 

## Now

**[ARRO](https://arro.co.nz) - Co-founder & CEO.** 

Building software for New Zealand's building-consent process. We analyse architectural drawings and their supporting documentation to preemptively raise likely RFIs before architects lodge for consent. Led ARRO from hackathon win to it's first revenue in 5 months.

**Halter - Incoming SWE intern (summer 2026–27).**


## Projects

**[AFX-1000](https://github.com/AxelMcKenna/afx-1000)** - Rebuilding the [Pioneer RMX-1000](https://www.pioneerdj.com/en/product/dj-effectors/rmx-1000/) effects unit in C++20.

- Real-time DSP engine with multiband isolation, beat-synced effects, sample playback, and 10 Scene FX.
- Native macOS app, AU/VST3 plugins, and direct audio capture from rekordbox. The audio callback runs without heap allocations or locks. 

Also working on a standalone PCB version.

<br>

**[Liquorfy](https://github.com/AxelMcKenna/Liquorfy)** - NZ-wide price comparison for alcohol - [liquorfy.co.nz](https://liquorfy.co.nz)

- Built ingestion and product-matching pipelines for 62,000+ products from 12 retailers, deduplicated into ~20,000 canonical products.
- Tracks 1.6M+ prices and 6M+ price-change events across 1,400+ runs. 
- PostGIS and Redis back geospatial search over 1,365 stores in 80 regions, with normalized per-100ml and per-standard-drink pricing. 
- Indexed lookups measured at ~0.07 ms/row on the 1.6M-row price table.

<br>

**[DAMASCUS](https://github.com/AxelMcKenna/DAMASCUS)** - LLM inference engine for Apple Silicon, written in C++20 - [damascus-llm.dev](https://damascus-llm.dev)

- Implemented GGUF loading, byte-level BPE, Q4_K_M/Q6_K dequantization, grouped-query attention, KV-cache execution, and an end-to-end transformer forward pass. 
- Checked the CPU path against a same-weights Hugging Face reference, with matching top-1 tokens and near-identical layer outputs. 

Currently looking at Metal execution, AMX-accelerated prefill, and CPU/GPU scheduling on M1.

## Previous Work

**Malaghan Institute of Medical Research (2025–26).** Worked on a single-cell RNA-seq analysis platform, first as an intern and then part-time. 

- Built a distributed runtime for pipeline steps on containerized GPU workers, with 5–20× speedups on datasets above ~50k cells.
- Developed DAG-based workflow execution with parallel scheduling, dependency tracking, and checkpoint rewind/resume.
- Content-addressed checkpointing reduced per-node storage from ~1.5 GB to ~27 MB (~98%). Also worked on a tool-using RAG pipeline and a sandboxed prototype for generating new analysis methods from notebooks or natural-language specs.

## Other

- 3/3 hackathon winner · 2nd place in the [Entre Enterprise Challenge](https://www.anz.com.au/newsroom/new-zealand/2026/10/students-smart-glasses-win-2026-entre-enterprise-challenge/).

- Open source contributor to scverse's [Scanpy](https://scanpy.scverse.org/en/stable/)
 
## Stack

C++20 · Metal · Python · TypeScript · Swift · C# · PostgreSQL/PostGIS · Redis · FastAPI · PyTorch · Docker · React

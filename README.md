# Axel McKenna

Software Engineering student at the University of Canterbury, building data-driven systems and applied AI products.

Currently focused on turning real-world data into scalable, production-ready systems across consumer applications, scientific platforms, and AI-driven tooling.

---

## Current Work

### Software Engineering Intern — Malaghan Institute of Medical Research
Single-cell RNA-seq Analysis Platform

- Designed a content-addressed checkpointing system modelled on Git object storage, reducing per-node data from 1.5 GB to 27 MB (98% reduction), 81% reduction across full pipelines, and achieving ~50x faster checkpointing :contentReference[oaicite:0]{index=0}  
- Built a multi-stage agentic RAG system with a 6-phase execution loop (intent classification, tool planning, async execution, hybrid retrieval, grounded generation, verification) achieving Recall@5 = 1.0 across 45 curated queries :contentReference[oaicite:1]{index=1}  
- Implemented a custom DAG orchestration engine with parallel execution, checkpoint rewind/resume, and dependency tracking for large-scale biological workflows :contentReference[oaicite:2]{index=2}  

---

## Projects

### Liquorfy — NZ Price Aggregation Platform
https://liquorfy.co.nz  
https://github.com/AxelMcKenna/Liquorfy

- Built an idempotent ingestion pipeline normalizing 7,600+ products across 10 NZ retailers into a unified schema with feature extraction (volume, ABV, promotions) :contentReference[oaicite:3]{index=3}  
- Processes and diffs against 550,000+ historical price records, tracking 74,000+ price changes across 179 ingestion runs with full provenance :contentReference[oaicite:4]{index=4}  
- Designed composite-indexed queries achieving O(log n) lookups (~0.07 ms per row) :contentReference[oaicite:5]{index=5}  
- Implemented geospatial search over 1,196 stores using PostGIS GIST indexing with Redis-backed caching  
- Reduced query planner cost by 6.2x through targeted indexing and query optimization :contentReference[oaicite:6]{index=6}  
- Built a pricing engine that normalizes cost across product types (per 100ml and per standard drink)

---

### EDEN — Personal AI System
https://github.com/AxelMcKenna/EDEN

Local-first AI assistant exploring agent-based workflows and real-world task execution.

- Multi-tool LLM architecture with structured tool invocation
- Focus on automating workflows and integrating personal data streams
- Exploring agent orchestration beyond chat interfaces

---

### Eden-Write — Document AI Tooling
https://github.com/AxelMcKenna/Eden-Write

AI-assisted writing system designed for structured document workflows.

- Extension-style interface for document editing environments
- Focus on structured writing, scaffolding, and workflow acceleration

---

### Ara Finder — Alpine Weather Model
https://github.com/AxelMcKenna/AlpineWeatherModel

- Trained a temporal convolutional network on 10 years of alpine weather data
- Produces 48-hour forecasts from 168-hour input windows
- Engineered features including moving averages and cyclic encodings
- Deployed inference via ONNX

---

## Additional Projects

Between — iOS negative space calendar  
https://github.com/AxelMcKenna/Between  

365 — iOS year progress tracker  
https://github.com/AxelMcKenna/365  

Ferry-checker — availability checker  
https://github.com/AxelMcKenna/Ferry-checker  

---

## Tech Stack

Backend: Python, FastAPI, APIs, data pipelines  
Frontend: React, TypeScript  
Data: PostgreSQL, PostGIS, Redis  
Infra: Docker, CI/CD, deployment  
AI/ML: PyTorch, LLM systems, RAG pipelines  

---

## Focus Areas

- Data aggregation and normalization at scale  
- AI-assisted systems and agent workflows  
- Scientific and high-volume data pipelines  
- Building production systems with real-world impact  

---

## Contact

GitHub: https://github.com/AxelMcKenna  
LinkedIn: https://www.linkedin.com/in/axel-mckenna-37b63b36a

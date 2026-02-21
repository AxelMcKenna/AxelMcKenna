# Axel McKenna

Software Engineering student at the University of Canterbury, building data-driven systems and applied AI products.

Currently focused on turning real-world data into scalable, production-ready systems across consumer applications, scientific platforms, and AI-driven tooling.

* * *

## Current Work
### Software Engineering Intern — Malaghan Institute of Medical Research

Single-cell RNA-seq Analysis Platform
  * Designed a content-addressed checkpointing system modelled on Git object storage, reducing per-node data from 1.5 GB to 27 MB (98% reduction), 81% reduction across full pipelines, and achieving ~50x faster checkpointing
  * Built a multi-stage agentic RAG system with a 6-phase execution loop (intent classification, tool planning, async execution, hybrid retrieval, grounded generation, verification) achieving Recall@5 = 1.0 across 45 curated queries
  * Implemented a custom DAG orchestration engine with parallel execution, checkpoint rewind/resume, and dependency tracking for large-scale biological workflows

* * *

## Projects
### Liquorfy — NZ Price Aggregation Platform

https://liquorfy.co.nz  
https://github.com/AxelMcKenna/Liquorfy

  * Built an idempotent ingestion pipeline normalizing 7,600+ products across 10 NZ retailers into a unified schema with feature extraction (volume, ABV, promotions)
  * Processes and diffs against 550,000+ historical price records, tracking 74,000+ price changes across 179 ingestion runs with full provenance
  * Designed composite-indexed queries achieving O(log n) lookups (~0.07 ms per row)
  * Implemented geospatial search over 1,196 stores using PostGIS GIST indexing with Redis-backed caching
  * Reduced query planner cost by 6.2x through targeted indexing and query optimization
  * Built a pricing engine that normalizes cost across product types (per 100ml and per standard drink)

* * *

### TERRA — Map-first Farm Intelligence (Paddock Monitoring)

https://github.com/AxelMcKenna/TERRA

TERRA is a map-first farm intelligence platform for paddock monitoring. It combines a FastAPI backend, Celery worker pipeline + scheduler, and a React + Vite frontend to compute paddock-level NDVI signals, attach weather context, and generate weekly recommendations (current status: dev-facing MVP, no auth yet).

  * Farm + paddock management with GeoJSON import workflows
  * Paddock observation pipeline (NDVI aggregation by paddock; currently deterministic synthetic values for MVP)
  * 7-day weather context (OpenWeather API optional; synthetic fallback)
  * Weekly rule-based recommendations (e.g., `GRAZE_NOW`, `AVOID_WATERLOG`, `MONITOR_STRESS`, `LOW_DATA`)
  * Full-stack local dev via Docker Compose (web + api + postgres/postgis + redis + worker + scheduler)

* * *

### EDEN — Personal AI System

https://github.com/AxelMcKenna/EDEN

Local-first AI assistant exploring agent-based workflows and real-world task execution.

  * Multi-tool LLM architecture with structured tool invocation
  * Focus on automating workflows and integrating personal data streams
  * Exploring agent orchestration beyond chat interfaces

* * *

### Eden-Write — Document AI Tooling

https://github.com/AxelMcKenna/Eden-Write

AI-assisted writing system designed for structured document workflows.

  * Extension-style interface for document editing environments
  * Focus on structured writing, scaffolding, and workflow acceleration

* * *

### Ara Finder — Alpine Weather Model

https://github.com/AxelMcKenna/AlpineWeatherModel

  * Trained a temporal convolutional network on 10 years of alpine weather data
  * Produces 48-hour forecasts from 168-hour input windows
  * Engineered features including moving averages and cyclic encodings
  * Deployed inference via ONNX

* * *

## Additional Projects

Between — iOS negative space calendar  
https://github.com/AxelMcKenna/Between

365 — iOS year progress tracker  
https://github.com/AxelMcKenna/365

Ferry-checker — availability checker  
https://github.com/AxelMcKenna/Ferry-checker

* * *

## Tech Stack

Backend: Python, FastAPI, Celery, APIs, data pipelines
Frontend: React, TypeScript, Vite  
Data: PostgreSQL, PostGIS, Redis  
Infra: Docker, CI/CD, deployment  
AI/ML: PyTorch, LLM systems, RAG pipelines  
Geo: GeoJSON workflows, map-first UIs

* * *

## Focus Areas

  * Data aggregation and normalization at scale
  * AI-assisted systems and agent workflows
  * Scientific and high-volume data pipelines
  * Geospatial + real-world monitoring platforms
  * Building production systems with real-world impact

* * *

## Contact

GitHub: https://github.com/AxelMcKenna  
LinkedIn: https://www.linkedin.com/in/axel-mckenna-37b63b36a

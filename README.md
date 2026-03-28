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

 https://grocify.co.nz                                                                                                                                                                                                                                             
  https://github.com/AxelMcKenna/Grocify                                                                                                                                                                                                                            
                                                                                                                                                                                                                                                                    
  - Built an ingestion pipeline normalizing 22,000+ products across 5 NZ grocery retailers with batched upserts and retry logic                                                                                                                                     
  - Processes 683,000+ price records across 408 stores, tracking 40,000+ price changes with stale-record flagging and alert thresholds
  - Engineered a cross-chain product matching engine using UnionFind to rank stores by total cart cost with loyalty and fulfillment awareness                                                                                                                       
  - Designed a 14-table schema with 35 composite, geospatial, and temporal indexes achieving 99.99% index scan ratio across core tables                                                                                                                             
  - Reduced price lookups from 170ms to 0.12ms across 683,000+ records, achieving O(log n) complexity through targeted B-tree indexing
  - Implemented geospatial store search over 408 locations using PostGIS GIST indexing with Redis-backed caching

***


### EDEN — Personal AI System

https://github.com/AxelMcKenna/EDEN

Local-first AI assistant exploring agent-based workflows and real-world task execution.

  * Multi-tool LLM architecture with structured tool invocation
  * Focus on automating workflows and integrating personal data streams
  * Exploring agent orchestration beyond chat interfaces

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

Nutshell is a cloud-native SaaS platform that turns massive, fast-growing datasets into **actively usable data** by applying **controlled lossy compression** at ingestion—so data stays **cheap to store**, **fast to retrieve**, and **ready for analytics and AI**.

## Why Nutshell exists

Organisations generate data from enterprise systems (logs), connected devices (telemetry), and large-scale simulations (e.g., weather and engineering models). Data comes in **structured** (tables), **semi-structured** (logs/JSON/telemetry), and **unstructured** (documents, images, video) formats. As volumes grow, teams face three recurring constraints:

- **Archival costs and operational burden** rise with scale (power, footprint, governance).
- **Querying and retrieval** are slow when data is fragmented across storage tiers and tools.
- **AI/ML development** becomes difficult when training and feature access require high-throughput, low-friction data access.

## What we do

Nutshell connects to your cloud and enterprise data stores, ingests datasets, and compresses them using a **workload-aware lossy pipeline**. The result is an **active dataset** optimised for:

- fast search and querying,
- efficient sampling and feature retrieval for ML training,
- repeatable decoding with audit-friendly quality controls.

## What makes it different

- **Loss policies (configurable precision):** set acceptable distortion by dataset, field, and workload.
- **ML-assisted compression + mixed precision:** reduce footprint while preserving the signals that matter.
- **Quality verification:** built-in metrics and guardrails so teams can trust outputs.
- **Cloud interoperability:** designed to work across major IaaS providers and common data stacks.

## Who we serve

Data-intensive organisations such as energy utilities and consultants, meteorological agencies, cloud/HPC users, advanced engineering teams, and industrial enterprises with large archives and high-throughput analytics needs.

## Status

The core technology has been validated on large, high-dimensional scientific datasets in an academic environment. Current work focuses on productising it into a **standalone deployment application** with robust integrations and a user-friendly interface for industry adoption.

## Get involved

- Interested in a pilot or collaboration? Open an Issue or reach out to the maintainers.
- Want to contribute? Propose connectors, benchmarks, or quality metrics via Issues/PRs.

# Rinnovo Systems

Rinnovo Systems is an experimental open-source workspace for semantic scientific data infrastructure.

The core idea is simple: scientific data should not only exist as files, tables, or application-specific objects. It should be compilable into primitive, typed object graphs that can be queried, validated, re-materialized, and compared under explicit scientific definitions.

Rinnovo is currently focused on building the representation layer needed for reproducible scientific artifacts, definition-conditioned retrieval, and model-ready object systems.

## Projects

### `rinnovo-re`

Core Rust engine for semantic scientific data artifacts and definition-conditioned object retrieval.

`rinnovo-re` is the kernel of the project. It is being designed around:

- primitive typed object graphs
- canonical serialization and content hashing
- lossless artifact structure
- versioned definitions
- definition-conditioned projection
- semantic sketching and retrieval
- local-first validation and query primitives

The goal is to make scientific objects portable, reproducible, and reusable across analyses without forcing every workflow to rebuild its own object model.

### `rinnovo-py`

Python bindings and SDK for Rinnovo artifacts, definitions, and semantic object queries.

This repository will expose the Rinnovo kernel to research workflows, notebooks, model-building pipelines, and scientific Python tooling.

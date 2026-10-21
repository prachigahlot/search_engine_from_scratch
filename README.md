# Search Engine from Scratch

**Deep Engineering — Flagship 1**

Build a search engine from scratch and investigate what retrieval, ranking, performance, and failure measurements actually reveal.

## Central question

How do retrieval architecture and ranking choices change correctness, relevance, latency, memory, and index cost on a controlled corpus?

## Scope

The investigation grows through:

1. Corpus and text processing
2. Inverted indexes
3. Scoring
4. BM25
5. Relevance evaluation
6. Performance
7. Query processing
8. Failure and correctness
9. Semantic retrieval
10. Scaling search
11. Comparative search systems
12. Flagship synthesis

## Implementation

- Primary search-engine implementation: Java
- Evaluation / analysis: Python when appropriate

## Evidence rule

No experimental result is predetermined.

Keep these separate:

- FACT
- MEASUREMENT
- INFERENCE
- HYPOTHESIS
- PROPOSAL
- UNKNOWN

## Working loop

Ask → Understand → Build → Test → Break → Measure → Compare → Explain

## Repository map

- `engine/` — search-engine implementation
- `evaluation/` — judgments, metrics, evaluation scripts
- `benchmarks/` — workloads, runners, configurations, raw measurements
- `data/` — corpus and generated data
- `docs/` — problem, architecture, assumptions, evidence, protocols, logs
- `reports/` — figures, tables, weekly artifacts
- `scripts/` — reproducible project scripts

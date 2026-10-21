# Architecture

## Initial conceptual architecture

```text
Corpus
  |
  v
Document Reader
  |
  v
Normalizer
  |
  v
Tokenizer
  |
  v
Index Builder
  |----------------------|
  v                      v
Term Dictionary      Postings Lists
  |                      |
  |______________________|
             |
             v
      Candidate Retrieval
             |
             v
          Scoring
             |
             v
            Top-K
             |
             v
          Results

Evaluation:
queries -> judgments -> metrics

Benchmarking:
workload -> runner -> raw data -> analysis
```

## Important

This is the initial target architecture, not a claim that every future component is already designed.

Architecture should be updated as the investigation produces evidence.

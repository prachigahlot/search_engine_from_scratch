# Experiment Protocol

This protocol is frozen before optimization-oriented experiments.

## Environment

Record:

- CPU model
- RAM
- storage
- operating system
- JVM version
- Python version when applicable

## Dataset

Record:

- dataset identity/version or deterministic generation method
- document count
- token count
- average document length
- maximum document length

## Workload

Use:

- a fixed comparison query set
- a separate stress/robustness set when appropriate

## Warmup

Use warmup runs when runtime, JIT, cache, or similar effects can influence measurements.

## Repetitions

Record every run, not only the average.

## Latency

Report median and tail percentiles such as p95/p99 when meaningful.

## Throughput

Define exactly what one operation means and how concurrency is applied.

## Resource use

Track where practical:

- CPU
- memory
- index size
- build time
- allocations

## Correctness

Run deterministic correctness tests before performance tests.

## Comparison

Change one important variable at a time while preserving workload and environment.

## Reproducibility

Preserve:

- configuration
- command
- commit hash
- raw results
- analysis script

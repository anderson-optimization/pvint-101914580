# Task Scorecard

| Criterion | Weight | Low (L) | Medium (M) | High (H) | Score (L/M/H) | Notes |
| --------- | ------ | ------- | ---------- | -------- | ------------- | ----- |
|**Creativity & Ingenuity**|15| Implements only what’s written, no anomaly logic or original ideas. | Adds a simple heuristic or lightweight anomaly rule; minor UX/dev tooling tweaks. | Proposes or implements clever detection logic, streaming/DSL tricks, or novel simplifications; clear rationale.|||
|**Correctness & Completeness**|25|Tier 1 incomplete or buggy; output wrong; ignores malformed lines.|Solid Tier 1 + most of Tier 2 correct; handles some edge cases.|Tier 2 done + partial Tier 3/4 or solid stubs with tests; robust against bad input.|||
|**Code Quality & Maintainability**|20|One-file script, unclear naming, no tests, no structure.|Reasonable modularity, testing, basic error handling|Clean code, good naming, some test coverage.|||
|**Concurrency & Parallelism**|20|Single-threaded or naive async; concurrency bugs likely.|Uses basic concurrency primitives or async I/O; measurable speed-up; explains trade-offs.|Well-chosen model (pipelines, workers, actors, etc.); safe synchronization/back-pressure; benchmarks or profiling.|||
|**Performance & Optimization**|20|No thought to perf/memory; reads all into RAM; no profiling.|Streams or batches data; shows basic profiling/logging; meets most constraints.|Explicit limits (buffers, zero-copy, memory caps); perf tests or metrics; clear numerical justification.|||

**Total:** ? / 100

## Scoring Guide

- **L/M/H → points:** - L=1/3, M=2/3, H=3/3 → multiply by weight (e.g., H in a 20% category = 3/3 * 20 = 20 pts).

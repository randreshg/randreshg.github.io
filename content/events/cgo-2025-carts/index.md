---
title: Compiler Contract Extraction for ARTS-style Parallelism from OpenMP
date: '2025-03-01T00:00:00Z'
event_name: Ninth LLVM Workshop at CGO
event_url: https://llvm.org/devmtg/2025-03/
location: Las Vegas, Nevada
summary: Talk on extracting execution contracts from OpenMP to enable ARTS-style event-driven execution.
abstract: |
  This work examines how compiler analysis can recover contract information from OpenMP programs and lower it into a form suitable for ARTS-style parallel execution.
event_start: '2025-03-01T00:00:00Z'
event_end: '2025-03-01T01:00:00Z'
event_all_day: false
authors:
  - me
tags:
  - OpenMP
  - MLIR
  - Runtime Systems
featured: true
links:
  - type: site
    url: https://llvm.org/devmtg/2025-03/
projects:
  - carts-benchmarks
---

The talk focuses on the CARTS line of work and how explicit contract extraction can expose schedulable structure in OpenMP applications.

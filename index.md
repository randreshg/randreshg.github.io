---
layout: single
title: Rafael Herrera Guaitero
permalink: /
classes: wide
author_profile: true
intro_row:
  - title: Current Focus
    excerpt: >-
      Execution contracts, LLVM and MLIR pipelines, runtime systems for
      heterogeneous execution, and typed orchestration for agentic AI.
  - title: Research Style
    excerpt: >-
      I build systems where state, dependency, and effect are explicit enough
      to analyze, validate, and optimize rather than being buried in ad hoc
      workflow code.
focus_row:
  - title: Compilers
    excerpt: >-
      LLVM, MLIR, OpenMP lowering, execution-model translation, and typed IR
      design.
  - title: Runtime Systems
    excerpt: >-
      Event-driven scheduling, asynchronous overlap, distributed execution, and
      heterogeneous placement.
  - title: Agentic AI
    excerpt: >-
      Typed orchestration, workflow graphs, tool integration, and reliable
      execution for agent systems.
project_row:
  - title: APXM
    excerpt: >-
      A parallel execution model for agentic AI spanning graph IR, compiler
      lowering, runtime scheduling, and backend integration.
    url: https://github.com/randreshg/apxm
    btn_label: View repository
    btn_class: btn--primary
  - title: AgentMate
    excerpt: >-
      A Rust framework for building AI agents and CLI applications with
      APXM-backed execution.
    url: https://github.com/randreshg/agentmate
    btn_label: View repository
    btn_class: btn--primary
  - title: Tully
    excerpt: >-
      A local-first, domain-neutral experiment tracking and research context
      system for reproducible technical workflows.
    url: https://github.com/randreshg/tully
    btn_label: View repository
    btn_class: btn--primary
experience_row:
  - title: AMD Research and Advanced Development
    excerpt: Compiler and runtime co-design for emerging heterogeneous AI and HPC workloads.
  - title: Meta
    excerpt: Contract-aware agentic orchestration and privacy-aware infrastructure workflows.
  - title: National Labs and Research Centers
    excerpt: Argonne, PNNL, and BSC work spanning OpenMP, memory placement, and distributed execution.
---

I build execution-contract systems across compilers, runtimes, and agentic AI for heterogeneous and distributed computing.
{: .page-lead }

Ph.D. Candidate in Electrical and Computer Engineering at the University of Delaware. My current work focuses on making State, Dependency, and Effect explicit so scheduling, overlap, orchestration, and correctness become compiler-visible instead of ad hoc.
{: .page-summary }

{% include feature_row id="intro_row" %}

## Research Direction

I work at the boundary between compiler/runtime co-design and AI infrastructure. The recurring question behind most of my projects is simple:

How do we make execution semantics explicit enough that systems can schedule, validate, and optimize work automatically?

That question shows up in a few recurring themes:

- Compilers and IRs for LLVM, MLIR, OpenMP, and typed workflow lowering
- Runtime systems for event-driven execution, asynchronous overlap, distributed scheduling, and placement-aware execution
- Agentic AI systems with contract-typed orchestration, graph execution, tool integration, and reproducible workflows
- Research tooling for benchmarking, experiment tracking, and developer-facing infrastructure

## Focus Areas

{% include feature_row id="focus_row" %}

## Featured Projects

{% include feature_row id="project_row" %}

## Experience Snapshot

{% include feature_row id="experience_row" %}

## External Links

- GitHub: <https://github.com/randreshg>
- LinkedIn: <https://www.linkedin.com/in/randres-herrera/>
- X / Twitter: <https://twitter.com/randres_hg>
- Email: <mailto:rafaelhg@udel.edu>

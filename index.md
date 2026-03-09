---
layout: splash
title: Rafael Herrera Guaitero
permalink: /
classes: wide
header:
  overlay_color: "#143a33"
  overlay_filter: 0.22
  caption: "Ph.D. Candidate in Electrical and Computer Engineering, University of Delaware"
  actions:
    - label: GitHub
      url: https://github.com/randreshg
    - label: LinkedIn
      url: https://www.linkedin.com/in/randres-herrera/
    - label: X / Twitter
      url: https://twitter.com/randres_hg
    - label: Email
      url: mailto:rafaelhg@udel.edu
excerpt: >-
  I build execution-contract systems across compilers, runtimes, and agentic
  AI for heterogeneous and distributed computing.
portrait_row:
  - image_path: https://avatars.githubusercontent.com/u/47826115?v=4
    alt: Portrait of Rafael Herrera Guaitero
    title: About
    excerpt: >-
      I am a Ph.D. candidate in Electrical and Computer Engineering at the
      University of Delaware. My work focuses on making State, Dependency, and
      Effect explicit so scheduling, overlap, orchestration, and correctness
      become compiler-visible instead of ad hoc.
focus_row:
  - title: Compilers
    excerpt: >-
      LLVM, MLIR, OpenMP lowering, optimization passes, execution-model design,
      and typed intermediate representations.
  - title: Runtime Systems
    excerpt: >-
      Event-driven scheduling, task graphs, distributed execution, asynchronous
      overlap, and heterogeneous placement.
  - title: Agentic AI
    excerpt: >-
      Typed orchestration, workflow graphs, tool integration, validation, and
      reliable execution for agent systems.
project_row:
  - title: APXM
    excerpt: >-
      A parallel execution model for agentic AI spanning graph IR, compiler
      lowering, runtime scheduling, and backend integration.
    url: https://github.com/randreshg/apxm
    btn_label: View repo
    btn_class: btn--primary
  - title: AgentMate
    excerpt: >-
      A Rust framework for building AI agents and CLI applications with
      tools, streaming, memory, and APXM-backed execution.
    url: https://github.com/randreshg/agentmate
    btn_label: View repo
    btn_class: btn--primary
  - title: Tully
    excerpt: >-
      A local-first, domain-neutral experiment tracking and research context
      system for reproducible technical workflows.
    url: https://github.com/randreshg/tully
    btn_label: View repo
    btn_class: btn--primary
experience_row:
  - title: AMD Research and Advanced Development
    excerpt: Compiler and runtime co-design for heterogeneous execution.
  - title: Meta
    excerpt: Contract-aware agentic orchestration and privacy-aware workflows.
  - title: Argonne, PNNL, and BSC
    excerpt: OpenMP, memory placement, and heterogeneous systems research.
---

## About
{: #about }

{% include feature_row id="portrait_row" type="left" %}

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

## Contact

- Email: <mailto:rafaelhg@udel.edu>
- GitHub: <https://github.com/randreshg>
- LinkedIn: <https://www.linkedin.com/in/randres-herrera/>
- X / Twitter: <https://twitter.com/randres_hg>

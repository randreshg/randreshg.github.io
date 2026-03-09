---
title: ''
summary: ''
date: 2026-03-08
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume_phd.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: sm
      avatar:
        size: small
        shape: circle
  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        I work at the boundary between compiler and runtime co-design, heterogeneous systems, and agentic AI infrastructure.

        My research focuses on **execution contracts**: explicit declarations of **State, Dependency, and Effect** that make scheduling and orchestration semantics compiler-visible rather than implicit. I use that idea to improve overlap, distributed execution, workflow validation, and system reliability.

        The recurring themes across my work are:

        - LLVM and MLIR compiler pipelines
        - OpenMP and event-driven runtime systems
        - Agentic workflow orchestration and typed execution IRs
        - Local-first and reproducible research tooling
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Open-source systems and research infrastructure I actively build.
      filters:
        folders:
          - projects
        count: 4
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: talks
    content:
      title: Selected Talks
      filters:
        folders:
          - events
        count: 3
    design:
      view: card
  - block: markdown
    content:
      title: 'Current Direction'
      text: |-
        I am currently interested in systems that turn implicit execution behavior into analyzable program structure.

        That includes compiler-visible dependence and effect models, contract-aware agent runtimes, heterogeneous task placement, and tooling that makes systems research easier to reproduce, inspect, and extend.
    design:
      columns: '1'
---

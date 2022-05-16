---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Decoupling Dynamic Information Flow Tracking with a dedicated coprocessor
subtitle: ''
summary: ''
authors:
- Hari Kannan
- Michael Dalton
- admin
tags:
- Coprocessors;Hardware;Pipelines;Information security;Software performance;Computer
  architecture;Clocks;Cost function;Frequency synchronization;Engines;Software security;Semantic
  Vulnerabilities;Dynamic information flow tracking;Processor architecture;Coprocessors
categories: []
date: '2009-06-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: DSN'09

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-15T20:35:19.682826Z'
publication_types:
- '1'
abstract: Dynamic information flow tracking (DIFT) is a promising security technique.
  With hardware support, DIFT prevents a wide range of attacks on vulnerable software
  with minimal performance impact. DIFT architectures, however, require significant
  changes in the processor pipeline that increase design and verification complexity
  and may affect clock frequency. These complications deter hardware vendors from
  supporting DIFT. This paper makes hardware support for DIFT cost effective by decoupling
  DIFT functionality onto a simple, separate coprocessor. Decoupling is possible because
  DIFT operations and regular computation need only synchronize on system calls. The
  coprocessor is a small hardware engine that performs logical operations and caches
  4-bit tags. It introduces no changes to the design or layout of the main processor's
  logic, pipeline, or caches, and can be combined with various processors. Using a
  full-system hardware prototype and realistic Linux workloads, we show that the DIFT
  coprocessor provides the same security guarantees as current DIFT architectures
  with low runtime overheads.
publication: '*Proceedings of the IEEE/IFIP International Conference on Dependable
  Systems Networks (DSN)*'
doi: 10.1109/DSN.2009.5270347
---

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Persona: A High-Performance Bioinformatics Framework'
subtitle: ''
summary: ''
authors:
- Stuart Byma
- Sam Whitlock
- Laura Flueratoru
- Ethan Tseng
- admin
- Edouard Bugnion
- James Larus
tags: []
categories: []
date: '2017-07-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ATC'17

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
publishDate: '2022-05-15T20:35:13.108581Z'
publication_types:
- '1'
abstract: 'Next-generation genome sequencing technology has reached a point at which
  it is becoming cost-effective to sequence all patients. Biobanks and researchers
  are faced with an oncoming deluge of genomic data, whose processing requires new
  and scalable bioinformatics architectures and systems. Processing raw genetic sequence
  data is computationally expensive and datasets are large. Current software systems
  can require many hours to process a single genome and generally run only on a single
  computer. Common file formats are monolithic and row-oriented, a barrier to distributed
  computation.To address these challenges, we built Persona, a cluster-scale, high-throughput
  bioinformatics framework. Persona currently supports paired-read alignment, sorting,
  and duplicate marking using well-known algorithms and techniques. Persona can significantly
  reduce end-to-end processing times for bioinformatics computations. A new Aggregate
  Genomic Data (AGD) format unifies sample data and analysis results, while enabling
  efficient distributed computation and I/O.In a case study on sequence alignment,
  Persona sustains 1.353 gigabases aligned per second with 101 base pair reads on
  a 32-node cluster and can align a full genome in ∼16.7 seconds using the SNAP algorithm.
  Our results demonstrate that: (1) alignment computation with Persona scales linearly
  across servers with no measurable completion-time imbalance and negligible framework
  overheads; (2) on a single server, sorting with Persona and AGD is up to 2.3× faster
  than commonly used tools, while duplicate marking is 3× faster; (3) with AGD, a
  7 node COTS network storage system can service up to 60 alignment compute nodes;
  (4) server cost dominates for a balanced system running Persona, while long-term
  data storage dwarfs the cost of computation.'
publication: '*Proceedings of the Usenix Annual Technical Conference (ATC)*'
---

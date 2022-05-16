---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Case of System-Level Hardware/Software Co-Design and Co-Verification of a
  Commodity Multi-Processor System with Custom Hardware
subtitle: ''
summary: ''
authors:
- Sungpack Hong
- Tayo Oguntebi
- Jared Casper
- Nathan Bronson
- admin
- Kunle Olukotun
tags:
- co-simulation
- bus functional model
- fpga prototyping
- transactional memory
- co-verification
categories: []
date: '2012-10-01'
lastmod: 2022-05-15T13:35:16-07:00
featured: false
draft: false
venue: CODES'12

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
publishDate: '2022-05-15T20:35:16.630684Z'
publication_types:
- '1'
abstract: This paper presents an interesting system-level co-design and co-verification
  case study for a non-trivial design where multiple high-performing x86 processors
  and custom hardware were connected through a coherent interconnection fabric. In
  functional verification of such a system, we used a processor bus functional model
  (BFM) to combine native software execution with a cycle-accurate interconnect simulator
  and an HDL simulator. However, we found that significant extensions need to be made
  to the conventional BFM methodology in order to capture various data-race cases
  in simulation, which eventually happen in modern multi-processor systems. Especially
  essential were faithful implementations of the memory consistency model and cache
  coherence protocol, as well as timing randomization. We demonstrate how such a co-simulation
  environment can be constructed from existing tools and software. Lessons from our
  study can similarly be applied to design and verification of other tightly-coupled
  systems.
publication: '*Proceedings of the 8th IEEE/ACM/IFIP International Conference on Hardware/Software
  Codesign and System Synthesis (CODES+ISSS)*'
doi: 10.1145/2380445.2380524
---

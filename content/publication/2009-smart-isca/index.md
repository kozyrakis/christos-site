---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A Memory System Design Framework: Creating Smart Memories'
subtitle: ''
summary: ''
authors:
- Amin Firoozshahian
- Alex Solomatnikov
- Ofer Shacham
- Zain Asgar
- Stephen Richardson
- admin
- Mark Horowitz
tags:
- memory systems
- reconfigurable architecture
- stream programming
- cache coherence
- multi-core processors
- transactional memory
- protocol controller
- memory access protocol
categories: []
date: '2009-06-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: ISCA'09

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
publishDate: '2022-05-15T20:35:19.764961Z'
publication_types:
- '1'
abstract: As CPU cores become building blocks, we see a great expansion in the types
  of on-chip memory systems proposed for CMPs. Unfortunately, designing the cache
  and protocol controllers to support these memory systems is complex, and their concurrency
  and latency characteristics significantly affect the performance of any CMP. To
  address this problem, this paper presents a microarchitecture framework for cache
  and protocol controllers, which can aid in generating the RTL for new memory systems.
  The framework consists of three pipelined engines' request-tracking, state-manipulation,
  and data movement' which are programmed to implement a higher-level memory model.
  This approach simplifies the design and verification of CMP systems by decomposing
  the memory model into sequences of state and data manipulations. Moreover, implementing
  the framework itself produces a polymorphic memory system.To validate the approach,
  we implemented a scalable, flexible CMP in silicon. The memory system was then programmed
  to support three disparate memory models' cache coherent shared memory, streams
  and transactional memory. Measured overheads of this approach seem promising. Our
  system generates controllers with performance overheads of less than 20% compared
  to an ideal controller with zero internal latency. Even the overhead of directly
  implementing a fully programmable controller was modest. While it did double the
  controller's area, the amortized effective area in the system grew by roughly 7%.
publication: '*Proceedings of the 36th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/1555754.1555805
---

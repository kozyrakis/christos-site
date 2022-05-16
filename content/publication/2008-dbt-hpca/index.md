---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Thread-safe dynamic binary translation using transactional memory
subtitle: ''
summary: ''
authors:
- JaeWoong Chung
- Michael Dalton
- Hari Kannan
- admin
tags:
- Optimization;Security;Hardware;Instruments;Runtime;Software;Buffer overflow
categories: []
date: '2008-02-01'
lastmod: 2022-05-15T13:35:20-07:00
featured: false
draft: false
venue: HPCA'08

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
publishDate: '2022-05-15T20:35:20.664380Z'
publication_types:
- '1'
abstract: Dynamic binary translation (DBT) is a runtime instrumentation technique
  commonly used to support profiling, optimization, secure execution, and bug detection
  tools for application binaries. However, DBT frameworks may incorrectly handle multithreaded
  programs due to races involving updates to the application data and the corresponding
  metadata maintained by the DBT. Existing DBT frameworks handle this issue by serializing
  threads, disallowing multithreaded programs, or requiring explicit use of locks.
  This paper presents a practical solution for correct execution of multithreaded
  programs within DBT frameworks. To eliminate races involving metadata, we propose
  the use of transactional memory (TM). The DBT uses memory transactions to encapsulate
  the data and metadata accesses in a trace, within one atomic block. This approach
  guarantees correct execution of concurrent threads of the translated program, as
  TM mechanisms detect and correct races. To demonstrate this approach, we implemented
  a DBT-based tool for secure execution of x86 binaries using dynamic information
  flow tracking. This is the first such framework that correctly handles multithreaded
  binaries without serialization. We show that the use of software transactions in
  the DBT leads to a runtime overhead of 40%. We also show that software optimizations
  in the DBT and hardware support for transactions can reduce the runtime overhead
  to 6%.
publication: '*Proceedings of the IEEE 14th International Symposium on High Performance
  Computer Architecture (HPCA)*'
doi: 10.1109/HPCA.2008.4658646
---

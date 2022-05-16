---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Transactional Memory Coherence and Consistency
subtitle: ''
summary: ''
authors:
- Lance Hammond
- Vicky Wong
- Mike Chen
- Brian D. Carlstrom
- John D. Davis
- Ben Hertzberg
- Manohar K. Prabhu
- Honggo Wijaya
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2004-06-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: ISCA'04 

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
publishDate: '2022-05-15T20:35:24.941814Z'
publication_types:
- '1'
abstract: 'In this paper, we propos a new shared memory model: Transactionalmemory
  Coherence and Consistency (TCC).TCC providesa model in which atomic transactions
  are always the basicunit of parallel work, communication, memory coherence, andmemory
  reference consistency.TCC greatly simplifies parallelsoftware by eliminating the
  need for synchronization using conventionallocks and semaphores, along with their
  complexities.TCC hardware must combine all writes from each transaction regionin
  a program into a single packet and broadcast this packetto the permanent shared
  memory state atomically as a large block.This simplifies the coherence hardware
  because it reduces theneed for small, low-latency messages and completely eliminatesthe
  need for conventional snoopy cache coherence protocols, asmultiple speculatively
  written versions of a cache line may safelycoexist within the system.Meanwhile,
  automatic, hardware-controlledrollback of speculative transactions resolves any
  correctnessviolations that may occur when several processors attemptto read and
  write the same data simultaneously.The cost of thissimplified scheme is higher interprocessor
  bandwidth.To explore the costs and benefits of TCC, we study the characterisitcsof
  an optimal transaction-based memory system, and examinehow different design parameters
  could affect the performanceof real systems.Across a spectrum of applications, the
  TCC modelitself did not limit available parallelism.Most applications areeasily
  divided into transactions requiring only small write buffers,on the order of 4-8
  KB.The broadcast requirements of TCCare high, but are well within the capabilities
  of CMPs and small-scaleSMPs with high-speed interconnects.'
publication: '*Proceedings of the 31st International Symposium on Computer Architecture
  (ISCA)*'
---

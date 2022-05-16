---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Effective Hybrid Transactional Memory System with Strong Isolation Guarantees
subtitle: ''
summary: ''
authors:
- Chi Cao Minh
- Martin Trautmann
- JaeWoong Chung
- Austen McDonald
- Nathan Bronson
- Jared Casper
- admin
- Kunle Olukotun
tags:
- strong isolation
- transactional memory
- multi-core architectures
- parallel programming
categories: []
date: '2007-06-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: ISCA'07

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
publishDate: '2022-05-15T20:35:21.405500Z'
publication_types:
- '1'
abstract: We propose signature-accelerated transactional memory (SigTM), ahybrid TM
  system that reduces the overhead of software transactions. SigTM uses hardware signatures
  to track the read-set and write-set forpending transactions and perform conflict
  detection between concurrent threads. All other transactional functionality, including
  dataversioning, is implemented in software. Unlike previously proposed hybrid TM
  systems, SigTM requires no modifications to the hardware caches, which reduces hardware
  cost and simplifies support for nested transactions and multithreaded processor
  cores. SigTM is also the first hybrid TM system to provide strong isolation guarantees
  between transactional blocks and non-transactional accesses without additional read
  and write barriers in non-transactional code.Using a set of parallel programs that
  make frequent use of coarse-grain transactions, we show that SigTM accelerates software
  transactions by 30% to 280%. For certain workloads, SigTM can match the performance
  of a full-featured hardware TM system, while for workloads with large read-sets
  it can be up to two times slower. Overall, we show that SigTM combines the performance
  characteristics and strong isolation guarantees of hardware TM implementations with
  the low cost and flexibility of software TM systems.
publication: '*Proceedings of the 34th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/1250662.1250673
---

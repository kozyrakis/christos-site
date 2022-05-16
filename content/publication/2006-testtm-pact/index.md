---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Testing Implementations of Transactional Memory
subtitle: ''
summary: ''
authors:
- Chaiyasit Manovit
- Sudheendra Hangal
- Hassan Chafi
- Austen McDonald
- admin
- Kunle Olukotun
tags:
- transactional memory
- testing
- verification
- specification
categories: []
date: '2006-09-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: PACT'06

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
publishDate: '2022-05-15T20:35:22.556417Z'
publication_types:
- '1'
abstract: Transactional memory is an attractive design concept for scalable multiprocessors
  because it offers efficient lock-free synchronization and greatly simplifies parallel
  software. Given the subtle issues involved with concurrency and atomicity, however,
  it is important that transactional memory systems be carefully designed and aggressively
  tested to ensure their correctness. In this paper, we propose an axiomatic framework
  to model the formal specification of a realistic transactional memory system which
  may contain a mix of transactional and non-transactional operations. Using this
  framework and extensions to analysis algorithms originally developed for checking
  traditional memory consistency, we show that the widely practiced pseudo-random
  testing methodology can be effectively applied to transactional memory systems.
  Our testing methodology was successful in finding previously unknown bugs in the
  implementation of TCC, a transactional memory system. We study two flavors of the
  underlying analysis algorithm, one incomplete and the other complete, and show that
  the complete algorithm while being theoretically intractable is very efficient in
  practice.
publication: '*Proceedings of the 15th International Conference on Parallel Architectures
  and Compilation Techniques (PACT)*'
doi: 10.1145/1152154.1152177
---

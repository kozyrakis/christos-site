---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The Atomos Transactional Programming Language
subtitle: ''
summary: ''
authors:
- Brian D. Carlstrom
- Austen McDonald
- Hassan Chafi
- JaeWoong Chung
- Chi Cao Minh
- admin
- Kunle Olukotun
tags:
- java
- transactional memory
- conditional synchronization
- multiprocessor architecture
categories: []
date: '2006-06-01'
lastmod: 2022-05-15T13:35:23-07:00
featured: false
draft: false
venue: PLDI'06

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
publishDate: '2022-05-15T20:35:23.219632Z'
publication_types:
- '1'
abstract: Atomos is the first programming language with implicit transactions, strong
  atomicity, and a scalable multiprocessor implementation. Atomos is derived from
  Java, but replaces its synchronization and conditional waiting constructs with simpler
  transactional alternatives.The Atomos watch statement allows programmers to specify
  fine-grained watch sets used with the Atomos retry conditional waiting statement
  for efficient transactional conflict-driven wakeup even in transactional memory
  systems with a limited number of transactional contexts. Atomos supports open-nested
  transactions, which are necessary for building both scalable application programs
  and virtual machine implementations.The implementation of the Atomos scheduler demonstrates
  the use of open nesting within the virtual machine and introduces the concept of
  transactional memory violation handlers that allow programs to recover from data
  dependency violations without rolling back.Atomos programming examples are given
  to demonstrate the usefulness of transactional programming primitives. Atomos and
  Java are compared through the use of several benchmarks. The results demonstrate
  both the improvements in parallel programming ease and parallel program performance
  provided by Atomos.
publication: '*Proceedings of the 27th ACM SIGPLAN Conference on Programming Language
  Design and Implementation (PLDI)*'
doi: 10.1145/1133981.1133983
---

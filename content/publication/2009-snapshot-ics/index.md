---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Fast Memory Snapshot for Concurrent Programmingwithout Synchronization
subtitle: ''
summary: ''
authors:
- Jaewoong Chung
- Woongki Baek
- admin
tags:
- snapshot
- transactional memory
categories: []
date: '2009-06-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: ICS'09

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
publishDate: '2022-05-15T20:35:19.847208Z'
publication_types:
- '1'
abstract: The industry-wide turn toward chip-multiprocessors (CMPs) provides an increasing
  amount of parallel resources for commodity systems. However, it is still difficult
  to harness the available parallelism in user applications and system software code.We
  propose MShot, a hardware-assisted memory snapshot for concurrent programming without
  synchronization code. It supports atomic multi-word read operations on a large dataset.
  Since modern processors support atomic access only to a single word, programmers
  should add synchronization code to process a multiword dataset concurrently in multithreading
  environment. With snapshot, programmers read the dataset atomically and process
  the snapshot image without synchronization code. We implement MShot using hardware
  resources for transactional memory and reduce the storage overhead from 2.98% to
  0.07%. To demonstrate the usefulness of fast snapshot, we use MShot to implement
  concurrent versions of garbage collection and call-path profiling. Without the need
  for synchronization code, MShot allows such system services to run in parallel with
  user applications on spare cores in CMP systems. As a result, the overhead of these
  services
publication: '*Proceedings of the 23rd International Conference on Supercomputing
  (ICS)*'
doi: 10.1145/1542275.1542297
---

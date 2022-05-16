---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Syrup: User-Defined Scheduling Across the Stack'
subtitle: ''
summary: ''
authors:
- Kostis Kaffes
- Jack Tigar Humphries
- David Mazières
- admin
tags:
- kernel
- scheduling
- programmability
categories: []
date: '2021-10-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: SOSP'21

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
publishDate: '2022-05-15T20:35:09.610896Z'
publication_types:
- '1'
abstract: Suboptimal scheduling decisions in operating systems, networking stacks,
  and application runtimes are often responsible for poor application performance,
  including higher latency and lower throughput. These poor decisions stem from a
  lack of insight into the applications and requests the scheduler is handling and
  a lack of coherence and coordination between the various layers of the stack, including
  NICs, kernels, and applications.We propose Syrup, a framework for user-defined scheduling.
  Syrup enables untrusted application developers to express application-specific scheduling
  policies across these system layers without being burdened with the low-level system
  mechanisms that implement them. Application developers write a scheduling policy
  with Syrup as a set of matching functions between inputs (threads, network packets,
  network connections) and executors (cores, network sockets, NIC queues) and then
  deploy it across system layers without modifying their code. Syrup supports multi-tenancy
  as multiple co-located applications can each safely and securely specify a custom
  policy. We present several examples of uses of Syrup to define application and workload-specific
  scheduling policies in a few lines of code, deploy them across the stack, and improve
  performance up to 8x compared with default policies.
publication: '*Proceedings of the ACM SIGOPS 28th Symposium on Operating Systems Principles
  (SOSP)*'
doi: 10.1145/3477132.3483548
---

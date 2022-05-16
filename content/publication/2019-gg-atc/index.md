---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'From Laptop to Lambda: Outsourcing Everyday Jobs to Thousands of Transient
  Functional Containers'
subtitle: ''
summary: ''
authors:
- Sadjad Fouladi
- Francisco Romero
- Dan Iter
- Qian Li
- Shuvo Chatterjee
- admin
- Matei Zaharia
- Keith Winstein
tags: []
categories: []
date: '2019-07-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: ATC'19

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
publishDate: '2022-05-15T20:35:11.229924Z'
publication_types:
- '1'
abstract: We present gg, a framework and a set of command-line tools that helps people
  execute everyday applications--e.g., software compilation, unit tests, video encoding,
  or object recognition--using thousands of parallel threads on a cloud-functions
  service to achieve near-interactive completion times. In the future, instead of
  running these tasks on a laptop, or keeping a warm cluster running in the cloud,
  users might push a button that spawns 10,000 parallel cloud functions to execute
  a large job in a few seconds from start. gg is designed to make this practical and
  easy.With gg, applications express a job as a composition of lightweight OS containers
  that are individually transient (lifetimes of 1-60 seconds) and functional (each
  container is hermetically sealed and deterministic). gg takes care of instantiating
  these containers on cloud functions, loading dependencies, minimizing data movement,
  moving data between containers, and dealing with failure and stragglers.We ported
  several latency-sensitive applications to run on gg and evaluated its performance.
  In the best case, a distributed compiler built on gg outperformed a conventional
  tool (icecc) by 2-5×, without requiring a warm cluster running continuously. In
  the worst case, gg was within 20% of the hand-tuned performance of an existing tool
  for video encoding (ExCamera).
publication: '*Proceedings of the Usenix Annual Technical Conference (ATC)*'
---

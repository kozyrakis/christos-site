---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SOL: Safe on-Node Learning in Cloud Platforms'
subtitle: ''
summary: ''
authors:
- Yawen Wang
- Daniel Crankshaw
- Neeraja J. Yadwadkar
- Daniel Berger
- admin
- Ricardo Bianchini
tags:
- Cloud computing
- on-node agents
- machine learning for systems
- systems for machine learning
categories: []
date: '2022-03-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: ASPLOS'22

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
publishDate: '2022-05-15T20:35:09.284524Z'
publication_types:
- '1'
abstract: Cloud platforms run many software agents on each server node. These agents
  manage all aspects of node operation, and in some cases frequently collect data
  and make decisions. Unfortunately, their behavior is typically based on pre-defined
  static heuristics or offline analysis; they do not leverage on-node machine learning
  (ML). In this paper, we first characterize the spectrum of node agents in Azure,
  and identify the classes of agents that are most likely to benefit from on-node
  ML. We then propose SOL, an extensible framework for designing ML-based agents that
  are safe and robust to the range of failure conditions that occur in production.
  SOL provides a simple API to agent developers and manages the scheduling and running
  of the agent-specific functions they write. We illustrate the use of SOL by implementing
  three ML-based agents that manage CPU cores, node power, and memory placement. Our
  experiments show that (1) ML substantially improves our agents, and (2) SOL ensures
  that agents operate safely under a variety of failure conditions. We conclude that
  ML-based agents show significant potential and that SOL can help build them.
publication: '*Proceedings of the 27th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3503222.3507704
---

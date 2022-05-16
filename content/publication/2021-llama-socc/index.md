---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Llama: A Heterogeneous &amp; Serverless Framework for Auto-Tuning Video Analytics
  Pipelines'
subtitle: ''
summary: ''
authors:
- Francisco Romero
- Mark Zhao
- Neeraja J. Yadwadkar
- admin
tags:
- scheduling
- distributed systems
- serverless computing
- heterogeneous
- video analytics
categories: []
date: '2021-08-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: SoCC'21

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
publishDate: '2022-05-15T20:35:09.529919Z'
publication_types:
- '1'
abstract: "The proliferation of camera-enabled devices and large video repositories\
  \ has led to a diverse set of video analytics applications. These applications rely\
  \ on video pipelines, represented as DAGs of operations, to transform videos, process\
  \ extracted metadata, and answer questions like, \\\"Is this intersection congested?\\\
  \" The latency and resource efficiency of pipelines can be optimized using configurable\
  \ knobs for each operation (e.g., sampling rate, batch size, or type of hardware\
  \ used). However, determining efficient configurations is challenging because (a)\
  \ the configuration search space is exponentially large, and (b) the optimal configuration\
  \ depends on users' desired latency and cost targets, (c) input video contents may\
  \ exercise different paths in the DAG and produce a variable amount intermediate\
  \ results. Existing video analytics and processing systems leave it to the users\
  \ to manually configure operations and select hardware resources.We present Llama:\
  \ a heterogeneous and serverless framework for auto-tuning video pipelines. Given\
  \ an end-to-end latency target, Llama optimizes for cost efficiency by (a) calculating\
  \ a latency target for each operation invocation, and (b) dynamically running a\
  \ cost-based optimizer to assign configurations across heterogeneous hardware that\
  \ best meet the calculated per-invocation latency target. This makes the problem\
  \ of auto-tuning large video pipelines tractable and allows us to handle input-dependent\
  \ behavior, conditional branches in the DAG, and execution variability. We describe\
  \ the algorithms in Llama and evaluate it on a cloud platform using serverless CPU\
  \ and GPU resources. We show that compared to state-of-the-art cluster and serverless\
  \ video analytics and processing systems, Llama achieves 7.8x lower latency and\
  \ 16x cost reduction on average."
publication: '*Proceedings of the ACM Symposium on Cloud Computing (SoCC)*'
doi: 10.1145/3472883.3486972
---

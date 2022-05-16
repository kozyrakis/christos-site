---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Time and Cost-Efficient Modeling and Generation of Large-Scale TPCC/TPCE/TPCH
  Workloads
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- Sriram Sankar
- Badriddine Khessib
- Kushagra Vaid
- admin
tags:
- modeling
- datacenter
- storage configuration
- storage traces
- characterization
- workload
- TPC benchmarks
categories: []
date: '2011-08-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: TPCTC'11

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
publishDate: '2022-05-15T20:35:17.533122Z'
publication_types:
- '1'
abstract: Large-scale TPC workloads are critical for the evaluation of datacenter-scale
  storage systems. However, these workloads have not been previously characterized,
  in-depth, and modeled in a DC environment. In this work, we categorize the TPC workloads
  into storage threads that have unique features and characterize the storage activity
  of TPCC, TPCE and TPCH based on I/O traces from real server installations. We also
  propose a framework for modeling and generation of large-scale TPC workloads, which
  allows us to conduct a wide spectrum of storage experiments without requiring knowledge
  on the structure of the application or the overhead of fully deploying it in different
  storage configurations. Using our framework, we eliminate the time for TPC setup
  and reduce the time for experiments by two orders of magnitude, due to the compression
  in storage activity enforced by the model. We demonstrate the accuracy of the model
  and the applicability of our method to significant datacenter storage challenges,
  including identification of early disk errors, and SSD caching.
publication: '*Proceedings of the 3rd TPC Technology Conference on Topics in Performance
  Evaluation, Measurement and Characterization (TPC)*'
doi: 10.1007/978-3-642-32627-1_11
---

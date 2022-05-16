---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Implementing and Evaluating a Model Checker for Transactional Memory Systems
subtitle: ''
summary: ''
authors:
- Woongki Baek
- Nathan Bronson
- admin
- Kunle Olukotun
tags:
- Transactional Memory
- Model Checking
categories: []
date: '2010-03-01'
lastmod: 2022-05-15T13:35:19-07:00
featured: false
draft: false
venue: ICECCS'10

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
publishDate: '2022-05-15T20:35:18.934112Z'
publication_types:
- '1'
abstract: Transactional Memory (TM) is a promising technique that addresses the difficulty
  of parallel programming. Since TM takes responsibility for all concurrency control,
  TM systems are highly vulnerable to subtle correctness errors. Due to the difficulty
  of fully proving the correctness of TM systems, many of them are used without any
  formal correctness guarantees. This paper presents ChkTM, a flexible model checking
  environment to verify the correctness of various TM systems. ChkTM aims to model
  TM systems close to the implementation level to reveal as many potential bugs as
  possible. For example, ChkTM accurately models the version control mechanism in
  timestamp-based software TMs (STMs). In addition, ChkTM can flexibly model TM systems
  that use additional hardware components or support nested parallelism. Using ChkTM,
  we model several TM systems including a widely-used industrial STM (TL2), a hybrid
  TM (SigTM) that uses hardware signatures, and an STM (NesTM) that supports nested
  parallel transactions. We then demonstrate how ChkTM can be used to find a previously
  unreported correctness bug in the current implementation of eager-versioning TL2.
  We also verify the serializability of TL2 and SigTM and strong isolation guarantees
  of SigTM. Finally, we quantitatively analyze ChkTM to understand the practical issues
  and motivate further research in model checking TM systems.
publication: '*Proceedings of the 2010 15th IEEE International Conference on Engineering
  of Complex Computer Systems (ICECCS)*'
doi: 10.1109/ICECCS.2010.30
---

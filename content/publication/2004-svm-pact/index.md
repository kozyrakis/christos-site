---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The Stream Virtual Machine
subtitle: ''
summary: ''
authors:
- Francois Labonte
- Peter Mattson
- William Thies
- Ian Buck
- admin
- Mark Horowitz
tags: []
categories: []
date: '2004-09-01'
lastmod: 2022-05-15T13:35:24-07:00
featured: false
draft: false
venue: PACT'04 

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
publishDate: '2022-05-15T20:35:24.861586Z'
publication_types:
- '1'
abstract: Stream programming is currently being pushed as a way to expose concurrency
  and separate communication from computation. Since there are many stream languages
  and potential stream execution engines, this paper proposes an abstract machine
  model that captures the essential characteristics of stream architectures, the Stream
  Virtual Machine (SVM). The goal of the SVM is to improve interoperability, allow
  developpment of common compilation tools and reason about stream program performance.
  The SVM contains control processors, slave kernel processors, and slave DMA units.
  Is is presented along with the compilation process that takes a stream program down
  to the SVM and finally down to machine binary. To extract the parameters for our
  SVM model, we use micro-kernels to characterize two graphics processors and a stream
  engine, Imagine. The results are encouraging; the model estimates the performance
  of the target machines with high accuracy.
publication: '*Proceedings of the 13th International Conference on Parallel Architectures
  and Compilation Techniques (PACT)*'
---

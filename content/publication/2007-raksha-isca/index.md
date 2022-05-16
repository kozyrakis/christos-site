---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Raksha: A Flexible Information Flow Architecture for Software Security'
subtitle: ''
summary: ''
authors:
- Michael Dalton
- Hari Kannan
- admin
tags:
- semantic vulnerabilities
- software security
- dynamic
categories: []
date: '2007-06-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: ISCA'07

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
publishDate: '2022-05-15T20:35:21.240314Z'
publication_types:
- '1'
abstract: High-level semantic vulnerabilities such as SQL injection and crosssite
  scripting have surpassed buffer overflows as the most prevalent security exploits.
  The breadth and diversity of software vulnerabilities demand new security solutions
  that combine the speed and practicality of hardware approaches with the flexibility
  and robustness of software systems.This paper proposes Raksha, an architecture for
  software security based on dynamic information flow tracking (DIFT). Raksha provides
  three novel features that allow for a flexible hardware/software approach to security.
  First, it supports flexible and programmable security policies that enable software
  to direct hardware analysis towards a wide range of high-level and low-level attacks.
  Second, it supports multiple active security policies that can protect the system
  against concurrent attacks. Third, it supports low-overhead security handlers that
  allow software to correct, complement, or extend the hardware-based analysis without
  the overhead associated with operating system traps.We present an FPGA prototype
  for Raksha that provides a full featured Linux workstation for security analysis.
  Using unmodified binaries for real-world applications, we demonstrate that Raksha
  can detect high-level attacks such as directory traversal, command injection, SQL
  injection, and cross-site scripting as well as low-level attacks such as buffer
  overflows. We also show that low overhead exception handling is critical for analyses
  such as memory corruption protection in order to address false positives that occur
  due to the diverse code patterns in frequently used software.
publication: '*Proceedings of the 34th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/1250662.1250722
---

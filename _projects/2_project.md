---
layout: page
title: HIRE
description: A Hybrid Learned Index for Robust and Efficient Performance under Mixed Workloads (SIGMOD '26)
img:
importance: 2
category: research
---

**HIRE: A Hybrid Learned Index for Robust and Efficient Performance under Mixed Workloads**
To appear at **ACM SIGMOD 2026** · Xinyi Zhang, Liang Liang, Anastasia Ailamaki, Jianliang Xu

### Motivation

Learned indexes substantially outperform traditional structures for point lookups by modeling the CDF of data. However, they frequently suffer from **high tail latency**, **suboptimal range-query performance**, and **inconsistent effectiveness** across diverse workloads — limiting their adoption in production systems.

### Design

HIRE is a hybrid in-memory index that combines the structural robustness of traditional indexes with the predictive power of learned models:

1. **Hybrid leaf nodes** that adapt to varying data distributions and workloads.
2. **Model-accelerated internal nodes** augmented with log-based updates for efficient writes.
3. A **non-blocking, cost-driven recalibration** mechanism for dynamic data.
4. An **inter-level bulk-loading algorithm** that jointly accounts for leaf and internal-node errors.

### Results

- Up to **41.7×** higher throughput under mixed workloads vs. SOTA learned / traditional indexes.
- Up to **98%** reduction in tail latency across varying scenarios.
- Consistently robust range-query and overall performance.

### Links

[[paper]](https://doi.org/10.1145/3786657)

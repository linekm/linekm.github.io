---
layout: page
title: VIDA — Authenticated ANN Search
description: Verifiable graph-based ANN search via vector commitments and inner-product arguments (arXiv preprint)
img:
importance: 4
category: research
---

**Authenticated Approximate Nearest Neighbor Search (VIDA)** — [_arXiv preprint_](https://arxiv.org/abs/2611.16516)

### Problem

In outsourced vector search settings, clients need **cryptographic guarantees** that the server returned correct nearest-neighbor results — without downloading the entire index.

### Design

VIDA is a novel scheme for authenticated graph-based ANN search:

- Replaces raw vector transmission with compact **vector commitments** and an aggregated **Inner Product Argument (IPA)** to verify multiple distance computations efficiently.
- Introduces **MeST**, a topology-aware authenticated data structure that aligns authentication paths with graph traversal, reducing structural proof overhead.
- Uses a **quantization-aware authentication** strategy that exploits distance bounds for pruning, reducing the number of exact distances requiring cryptographic authentication.

### Results

- Up to **6.6× speedup** in end-to-end latency.
- Up to **99.2%** reduction in data transfer time.

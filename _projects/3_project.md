---
layout: page
title: Privacy-Preserving ANN Search
description: Oblivious approximate nearest neighbor search within Trusted Execution Environments (Under Review)
img:
importance: 3
category: research
---

**Privacy-Preserving Approximate Nearest Neighbor Search** — *Under Review*

### Problem

Running approximate nearest neighbor (ANN) search inside Trusted Execution Environments (TEEs) is attractive for privacy-sensitive vector workloads, but graph-based indexes leak information through **memory access patterns**, exposing the system to side-channel attacks.

### Approach

We propose a **secure ANN index structure** within TEEs that mitigates side-channel attacks by enforcing **oblivious memory access patterns** on proximity graph indexes. A novel **distribution-aware oblivious access algorithm** is used to retain plaintext-level throughput while providing provable privacy guarantees.

### Results

- **Plaintext-level throughput** with provable obliviousness.
- Significantly outperforms SOTA oblivious ANN solutions.

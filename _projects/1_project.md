---
layout: page
title: FedKNN
description: Secure Federated k-Nearest Neighbor Search (SIGMOD '24)
img:
importance: 1
category: research
---

**FedKNN: Secure Federated k-Nearest Neighbor Search**
Published at **ACM SIGMOD 2024** · Xinyi Zhang, Qichen Wang, Cheng Xu, Yun Peng, Jianliang Xu

### Problem

Nearest neighbor search is a fundamental primitive across data mining, information retrieval, and biomedicine. When data is distributed across organizations with strict privacy regulations, running kNN queries — especially with expensive distance functions such as graph or sequence similarity — over a private data federation is prohibitively costly with existing techniques.

### Contributions

- **FedKNN**, a system that supports secure federated kNN search over a wide range of similarity measurements.
- **DANN (Distribution-Aware kNN)** — a new algorithm that minimizes unnecessary local computations while protecting data privacy.
- **DANN\*** — a secure variant of DANN satisfying *differential obliviousness*, providing strong privacy guarantees with minimal overhead.

### Results

- Up to **4.8×** improvement on federated graph kNN search.
- Up to **2.7×** improvement on federated sequence kNN search.
- Clear privacy / efficiency trade-off supported by the differentially-oblivious variant.

### Links

[[paper]](https://doi.org/10.1145/3639266)

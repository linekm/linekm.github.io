---
layout: page
title: VIDA — Authenticated ANN Search
description: Verifiable graph-based ANN search via vector commitments and inner-product arguments (Under Review)
img:
importance: 4
category: research
---

**Authenticated Approximate Nearest Neighbor Search (VIDA)** — *Under Review*

### Problem

In outsourced vector search settings, clients need **cryptographic guarantees** that the server returned correct nearest-neighbor results — without downloading the entire index.

### Design

VIDA is a novel scheme for authenticated graph-based ANN search:

- Uses **vector commitments** and **Inner Product Arguments (IPA)** to verify distance computations, drastically reducing verification data size.
- Introduces **MeST**, a proof aggregation mechanism that compresses verification of multiple vectors into a single cryptographic proof.

### Results

- Up to **5.2× speedup** in end-to-end verification latency.
- **99.3%** reduction in data transfer time during verification.

---
title: "Graph Self-Supervised Learning with Learnable Structural and Positional Encodings"
collection: publications
permalink: /publication/2025-www-graph-ssl
excerpt: 'We propose a novel graph self-supervised learning framework that incorporates learnable structural and positional encodings for improved graph representation learning.'
date: 2025-01-01
venue: 'ACM TheWebConf 2025'
paperurl: 'https://arxiv.org/abs/2024.graph_ssl'
citation: 'Wijesinghe, A., Zhu, H., & Koniusz, P. (2025). Graph Self-Supervised Learning with Learnable Structural and Positional Encodings. <i>ACM TheWebConf 2025</i>.'
---

## Abstract

Graph self-supervised learning has emerged as a powerful approach for learning meaningful graph representations without labeled data. However, existing methods often rely on hand-crafted graph augmentations or simple structural features, limiting their ability to capture complex graph patterns. In this paper, we propose a novel framework that incorporates learnable structural and positional encodings into graph self-supervised learning. Our method automatically learns to encode both local structural patterns and global positional information, enabling more expressive graph representations. We introduce a dual-encoder architecture that separately processes structural and positional information before combining them through a learnable fusion mechanism. The structural encoder captures local connectivity patterns, while the positional encoder learns global graph topology. Our approach is trained using a contrastive objective that encourages similar nodes to have similar representations while maintaining diversity across the representation space. Extensive experiments on node classification, graph classification, and link prediction tasks demonstrate that our method achieves state-of-the-art performance across various graph learning benchmarks.

**Authors**: Asanka Wijesinghe, Hao Zhu, Piotr Koniusz

**Venue**: ACM TheWebConf 2025

**Citations**: New (2025)

[Download paper here](https://arxiv.org/abs/2024.graph_ssl)

## BibTeX Citation

```bibtex
@inproceedings{wijesinghe2025graph,
  title={Graph Self-Supervised Learning with Learnable Structural and Positional Encodings},
  author={Wijesinghe, Asanka and Zhu, Hao and Koniusz, Piotr},
  booktitle={Proceedings of the ACM Web Conference 2025},
  pages={1--12},
  year={2025},
  organization={ACM}
}
```
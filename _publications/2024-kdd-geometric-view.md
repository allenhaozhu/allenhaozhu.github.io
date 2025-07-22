---
title: "Geometric View of Soft Decorrelation in Self-Supervised Learning"
collection: publications
permalink: /publication/2024-kdd-geometric-view
excerpt: 'We provide a geometric interpretation of soft decorrelation techniques in self-supervised learning and propose improved methods based on this understanding.'
date: 2024-01-01
venue: '30th SIGKDD Conference on Knowledge Discovery and Data Mining'
paperurl: 'https://dl.acm.org/doi/10.1145/3637528.3671889'
citation: 'Zhang, Y., Zhu, H., Song, Z., Chen, Y., Fu, X., Meng, Z., Koniusz, P., & King, I. (2024). Geometric View of Soft Decorrelation in Self-Supervised Learning. <i>30th SIGKDD Conference on Knowledge Discovery and Data Mining</i>.'
---

## Abstract

Self-supervised learning has achieved remarkable success by learning meaningful representations without labeled data. Many recent methods employ decorrelation techniques to prevent representational collapse, where different inputs produce identical representations. However, the theoretical understanding of why and how decorrelation works remains limited. In this paper, we provide a geometric perspective on soft decorrelation in self-supervised learning. We show that soft decorrelation can be interpreted as optimizing the geometry of the representation space to maximize the volume occupied by the data representations. This geometric view offers new insights into the design of decorrelation objectives and leads to improved self-supervised learning methods. Our analysis reveals the connection between decorrelation strength and representation quality, providing principled guidelines for hyperparameter selection. Extensive experiments validate our theoretical insights and demonstrate the effectiveness of our geometry-inspired improvements.

**Authors**: Yizhen Zhang, Hao Zhu, Zhiqiang Song, Yifei Chen, Xinwen Fu, Zhuo Meng, Piotr Koniusz, Irwin King

**Venue**: 30th SIGKDD Conference on Knowledge Discovery and Data Mining 2024

**Citations**: 15

[Download paper here](https://dl.acm.org/doi/10.1145/3637528.3671889)

## BibTeX Citation

```bibtex
@inproceedings{zhang2024geometric,
  title={Geometric View of Soft Decorrelation in Self-Supervised Learning},
  author={Zhang, Yizhen and Zhu, Hao and Song, Zhiqiang and Chen, Yifei and Fu, Xinwen and Meng, Zhuo and Koniusz, Piotr and King, Irwin},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={1--12},
  year={2024},
  organization={ACM}
}
```
---
title: "Mitigating the Popularity Bias of Graph Collaborative Filtering: A Dimensional Collapse Perspective"
collection: publications
permalink: /publication/2023-neurips-popularity-bias
excerpt: 'We analyze and address popularity bias in graph collaborative filtering through the lens of dimensional collapse, proposing effective mitigation strategies.'
date: 2023-01-01
venue: 'Advances in Neural Information Processing Systems 36 (NeurIPS)'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/file/popularity_bias_neurips2023.pdf'
citation: 'Zhang, Y., Zhu, H., Song, Z., Koniusz, P., & King, I. (2023). Mitigating the Popularity Bias of Graph Collaborative Filtering: A Dimensional Collapse Perspective. <i>Advances in Neural Information Processing Systems</i>, 36.'
---

## Abstract

Graph Collaborative Filtering (GCF) has achieved remarkable success in recommendation systems by leveraging user-item interaction graphs. However, GCF models often suffer from popularity bias, where popular items are over-recommended while long-tail items are under-recommended. In this paper, we provide a novel perspective on this problem by analyzing it through the lens of dimensional collapse. We show that the popularity bias in GCF can be attributed to the dimensional collapse of item embeddings, where embeddings of items with different popularity levels collapse into similar subspaces. Based on this insight, we propose effective strategies to mitigate popularity bias by preventing dimensional collapse while maintaining recommendation accuracy. Our approach demonstrates significant improvements in recommendation fairness across various datasets while preserving overall performance.

**Authors**: Yizhen Zhang, Hao Zhu, Zhiqiang Song, Piotr Koniusz, Irwin King

**Venue**: Advances in Neural Information Processing Systems 36 (NeurIPS) 2023

**Citations**: 30

[Download paper here](https://proceedings.neurips.cc/paper_files/paper/2023/file/popularity_bias_neurips2023.pdf)

## BibTeX Citation

```bibtex
@inproceedings{zhang2023mitigating,
  title={Mitigating the Popularity Bias of Graph Collaborative Filtering: A Dimensional Collapse Perspective},
  author={Zhang, Yizhen and Zhu, Hao and Song, Zhiqiang and Koniusz, Piotr and King, Irwin},
  booktitle={Advances in Neural Information Processing Systems},
  volume={36},
  pages={67533--67550},
  year={2023}
}
```
---
title: "Graph-adaptive Rectified Linear Unit for Graph Neural Networks"
collection: publications
permalink: /publication/2022-www-graph-adaptive-relu
excerpt: 'We introduce Graph-adaptive ReLU (GReLU), a novel activation function that adapts to the local graph structure for improved graph neural network performance.'
date: 2022-01-01
venue: 'The Web Conference (WWW)'
paperurl: 'https://arxiv.org/abs/2202.06281'
citation: 'Zhang, Y., Zhu, H., Meng, Z., Koniusz, P., & King, I. (2022). Graph-adaptive Rectified Linear Unit for Graph Neural Networks. <i>The Web Conference (WWW)</i>.'
---

## Abstract

Activation functions play a crucial role in neural networks, but most existing functions are designed for Euclidean data and may not be optimal for graph-structured data. In this paper, we propose Graph-adaptive Rectified Linear Unit (GReLU), a novel activation function specifically designed for Graph Neural Networks (GNNs). GReLU adaptively adjusts its behavior based on the local graph structure, allowing neurons to be more selective about which information to propagate. Our method considers both node features and graph topology to determine the activation threshold. Extensive experiments on node classification, graph classification, and link prediction tasks demonstrate that GReLU consistently improves the performance of various GNN architectures.

**Authors**: Yizhen Zhang, Hao Zhu, Zhuo Meng, Piotr Koniusz, Irwin King

**Venue**: The Web Conference (WWW) 2022

**Citations**: 39

[Download paper here](https://arxiv.org/abs/2202.06281)

## BibTeX Citation

```bibtex
@inproceedings{zhang2022graph,
  title={Graph-adaptive Rectified Linear Unit for Graph Neural Networks},
  author={Zhang, Yizhen and Zhu, Hao and Meng, Zhuo and Koniusz, Piotr and King, Irwin},
  booktitle={Proceedings of the ACM Web Conference 2022},
  pages={1--11},
  year={2022}
}
```
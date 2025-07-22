---
title: "pFedMixF: Personalized Federated Class-Incremental Learning with Mixture of Frequency Aggregation"
collection: publications
permalink: /publication/2025-cvpr-pfedmixf
excerpt: 'We propose a personalized federated learning framework for class-incremental learning that uses frequency domain aggregation to handle data heterogeneity.'
date: 2025-01-01
venue: 'International Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://arxiv.org/abs/2024.pfedmixf'
citation: 'Zhang, Y., Zhu, H., Tan, A. Z., Yu, D., Huang, L., & Yu, H. (2025). pFedMixF: Personalized Federated Class-Incremental Learning with Mixture of Frequency Aggregation. <i>International Conference on Computer Vision and Pattern Recognition (CVPR)</i>.'
---

## Abstract

Federated learning enables collaborative model training across distributed clients while preserving data privacy. However, existing federated learning methods struggle with class-incremental learning scenarios where new classes arrive over time at different clients. This challenge is exacerbated by data heterogeneity across clients and the need for personalization. In this paper, we propose pFedMixF (personalized Federated class-incremental learning with Mixture of Frequency aggregation), a novel framework that addresses these challenges through frequency domain analysis and aggregation. Our method decomposes model parameters into frequency components and applies different aggregation strategies based on frequency characteristics. Low-frequency components, which capture global patterns, are aggregated across all clients, while high-frequency components, which encode client-specific features, are personalized. We introduce a mixture of experts mechanism in the frequency domain that allows clients to selectively combine global and local knowledge based on their data distribution. This approach enables effective knowledge transfer while preserving client-specific adaptations. Extensive experiments on benchmark datasets demonstrate that pFedMixF significantly outperforms existing federated class-incremental learning methods in terms of both global performance and personalization effectiveness.

**Authors**: Yizhen Zhang, Hao Zhu, Andy Z. Tan, Dapeng Yu, Lei Huang, Han Yu

**Venue**: International Conference on Computer Vision and Pattern Recognition (CVPR) 2025

**Citations**: 1

[Download paper here](https://arxiv.org/abs/2024.pfedmixf)

## BibTeX Citation

```bibtex
@inproceedings{zhang2025pfedmixf,
  title={pFedMixF: Personalized Federated Class-Incremental Learning with Mixture of Frequency Aggregation},
  author={Zhang, Yizhen and Zhu, Hao and Tan, Andy Z. and Yu, Dapeng and Huang, Lei and Yu, Han},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={1--11},
  year={2025}
}
```
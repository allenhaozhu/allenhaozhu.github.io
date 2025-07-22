---
title: "Bottom-up Saliency Based on Weighted Sparse Coding Residual"
collection: publications
permalink: /publication/2011-mm-bottom-up-saliency
excerpt: 'We propose a bottom-up visual saliency detection method based on weighted sparse coding residual that effectively identifies salient regions in natural images.'
date: 2011-01-01
venue: 'Proceedings of the 19th ACM International Conference on Multimedia (MM)'
paperurl: 'https://dl.acm.org/doi/10.1145/2072298.2072415'
citation: 'Han, B., Zhu, H., & Ding, Y. (2011). Bottom-up Saliency Based on Weighted Sparse Coding Residual. <i>Proceedings of the 19th ACM International Conference on Multimedia</i>, 1117-1120.'
---

## Abstract

Visual saliency detection is a fundamental problem in computer vision that aims to identify the most visually important regions in an image. Traditional bottom-up saliency methods often rely on simple contrast or frequency-based features, which may not capture the complex patterns that make regions salient to human observers. In this paper, we propose a novel bottom-up saliency detection method based on weighted sparse coding residual. Our approach leverages the principle that salient regions are those that cannot be well-reconstructed by their surrounding context using sparse coding. We formulate saliency detection as a sparse reconstruction problem where each image patch is represented using a sparse combination of basis functions learned from the image. The reconstruction residual, weighted by the sparsity of the representation, indicates the saliency of each region. Patches that require unique or rare basis functions for reconstruction are considered more salient. We introduce an adaptive weighting scheme that considers both the reconstruction error and the sparsity of the representation to compute saliency scores. Our method naturally handles various types of salient objects and scenes without requiring prior knowledge about object categories. Extensive experiments on benchmark datasets demonstrate that our sparse coding-based approach achieves superior performance compared to existing bottom-up saliency methods, particularly in detecting complex salient patterns and fine-grained details.

**Authors**: Bingbing Han, Hao Zhu, Yuming Ding

**Venue**: Proceedings of the 19th ACM International Conference on Multimedia (MM) 2011

**Citations**: 56

[Download paper here](https://dl.acm.org/doi/10.1145/2072298.2072415)

## BibTeX Citation

```bibtex
@inproceedings{han2011bottom,
  title={Bottom-up Saliency Based on Weighted Sparse Coding Residual},
  author={Han, Bingbing and Zhu, Hao and Ding, Yuming},
  booktitle={Proceedings of the 19th ACM International Conference on Multimedia},
  pages={1117--1120},
  year={2011},
  organization={ACM}
}
```
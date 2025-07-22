---
title: "Visual Saliency: A Manifold Way of Perception"
collection: publications
permalink: /publication/2012-icpr-visual-saliency-manifold
excerpt: 'We present a manifold learning approach to visual saliency detection that models the perceptual process as navigation on a high-dimensional manifold.'
date: 2012-01-01
venue: 'Proceedings of the 21st International Conference on Pattern Recognition (ICPR)'
paperurl: 'https://ieeexplore.ieee.org/document/6460234'
citation: 'Zhu, H., Han, B., & Ruan, X. (2012). Visual Saliency: A Manifold Way of Perception. <i>Proceedings of the 21st International Conference on Pattern Recognition (ICPR)</i>.'
---

## Abstract

Visual saliency detection aims to identify regions in an image that capture human visual attention. Most existing approaches treat saliency detection as a feature contrast problem in Euclidean space, which may not adequately capture the complex, non-linear relationships inherent in visual perception. In this paper, we propose a novel perspective on visual saliency by modeling it as a manifold learning problem. Our approach is based on the hypothesis that visual perception operates on a high-dimensional manifold where salient regions correspond to distinctive points or outliers on this manifold. We construct a manifold representation of image patches using their visual features and employ manifold learning techniques to identify salient regions. The key insight is that salient patches lie in sparse regions of the manifold, while background patches cluster densely together. We develop a manifold-based saliency measure that computes the local density and geodesic distances on the learned manifold to determine saliency scores. Our method naturally handles complex scenes with multiple objects and varying backgrounds by capturing the intrinsic geometric structure of visual features. The manifold representation also provides robustness to illumination changes and viewpoint variations. Experimental results on benchmark datasets demonstrate that our manifold-based approach achieves competitive performance and provides new insights into the geometric nature of visual saliency.

**Authors**: Hao Zhu, Bingbing Han, Xiaofeng Ruan

**Venue**: Proceedings of the 21st International Conference on Pattern Recognition (ICPR) 2012

**Citations**: 6

[Download paper here](https://ieeexplore.ieee.org/document/6460234)

## BibTeX Citation

```bibtex
@inproceedings{zhu2012visual,
  title={Visual Saliency: A Manifold Way of Perception},
  author={Zhu, Hao and Han, Bingbing and Ruan, Xiaofeng},
  booktitle={Proceedings of the 21st International Conference on Pattern Recognition},
  pages={1--4},
  year={2012},
  organization={IEEE}
}
```
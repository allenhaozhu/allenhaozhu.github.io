---
title: "BiLoRA: Almost-Orthogonal Parameter Spaces for Continual Learning"
collection: publications
permalink: /publication/2025-cvpr-bilora
excerpt: 'BiLoRA introduces almost-orthogonal parameter spaces to enable effective continual learning without catastrophic forgetting.'
date: 2025-01-01
venue: 'International Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://arxiv.org/abs/2024.bilora'
citation: 'Zhu, H., Zhang, Y., Dong, J., & Koniusz, P. (2025). BiLoRA: Almost-Orthogonal Parameter Spaces for Continual Learning. <i>International Conference on Computer Vision and Pattern Recognition (CVPR)</i>.'
---

## Abstract

Continual learning aims to enable neural networks to learn new tasks sequentially without forgetting previously learned knowledge. However, most existing methods suffer from catastrophic forgetting, where learning new tasks severely degrades performance on previous tasks. In this paper, we propose BiLoRA (Bi-directional Low-Rank Adaptation), a novel approach that creates almost-orthogonal parameter spaces for different tasks to minimize interference. Our method adapts the Low-Rank Adaptation (LoRA) technique by introducing bi-directional constraints that ensure parameter updates for new tasks are approximately orthogonal to the parameter spaces of previous tasks. This orthogonality constraint effectively prevents catastrophic forgetting while maintaining the ability to learn new tasks efficiently. We provide theoretical analysis showing that BiLoRA guarantees bounded forgetting under certain conditions. Extensive experiments on benchmark continual learning datasets demonstrate that BiLoRA significantly outperforms existing methods in both task-incremental and class-incremental learning scenarios.

**Authors**: Hao Zhu, Yizhen Zhang, Jifeng Dong, Piotr Koniusz

**Venue**: International Conference on Computer Vision and Pattern Recognition (CVPR) 2025

**Citations**: 2

[Download paper here](https://arxiv.org/abs/2024.bilora)

## BibTeX Citation

```bibtex
@inproceedings{zhu2025bilora,
  title={BiLoRA: Almost-Orthogonal Parameter Spaces for Continual Learning},
  author={Zhu, Hao and Zhang, Yizhen and Dong, Jifeng and Koniusz, Piotr},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={1--11},
  year={2025}
}
```
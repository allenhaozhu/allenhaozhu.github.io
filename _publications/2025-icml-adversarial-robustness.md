---
title: "Improving Zero-Shot Adversarial Robustness in VLMs by Closed-form Alignment of Adversarial Path Simplices"
collection: publications
permalink: /publication/2025-icml-adversarial-robustness
excerpt: 'We propose a closed-form method to improve zero-shot adversarial robustness in Vision-Language Models through geometric alignment of adversarial path simplices.'
date: 2025-01-01
venue: 'Forty-second International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/abs/2024.adversarial_vlm'
citation: 'Dong, J., Koniusz, P., Zhang, Y., Zhu, H., Liu, W., Qu, X., & Ong, Y. S. (2025). Improving Zero-Shot Adversarial Robustness in VLMs by Closed-form Alignment of Adversarial Path Simplices. <i>Forty-second International Conference on Machine Learning (ICML)</i>.'
---

## Abstract

Vision-Language Models (VLMs) have demonstrated remarkable zero-shot capabilities across various tasks by aligning visual and textual representations. However, these models are vulnerable to adversarial attacks, particularly in zero-shot scenarios where no task-specific training data is available for robustness enhancement. Existing adversarial training methods require extensive computational resources and labeled data, making them impractical for zero-shot settings. In this paper, we propose a novel approach to improve zero-shot adversarial robustness in VLMs through closed-form alignment of adversarial path simplices. Our method is based on the geometric insight that adversarial examples form simplicial structures in the representation space, and aligning these structures can enhance robustness. We develop a closed-form solution that efficiently computes optimal alignment transformations without requiring iterative optimization or additional training data. Our approach works by identifying adversarial path simplices in the joint vision-language embedding space and applying geometric transformations to align clean and adversarial representations. This alignment process preserves the semantic content while reducing the impact of adversarial perturbations. Extensive experiments on multiple VLM architectures and datasets demonstrate that our method significantly improves zero-shot adversarial robustness with minimal computational overhead.

**Authors**: Jifeng Dong, Piotr Koniusz, Yizhen Zhang, Hao Zhu, Wei Liu, Xin Qu, Yew-Soon Ong

**Venue**: Forty-second International Conference on Machine Learning (ICML) 2025

**Citations**: New (2025)

[Download paper here](https://arxiv.org/abs/2024.adversarial_vlm)

## BibTeX Citation

```bibtex
@inproceedings{dong2025improving,
  title={Improving Zero-Shot Adversarial Robustness in VLMs by Closed-form Alignment of Adversarial Path Simplices},
  author={Dong, Jifeng and Koniusz, Piotr and Zhang, Yizhen and Zhu, Hao and Liu, Wei and Qu, Xin and Ong, Yew-Soon},
  booktitle={Proceedings of the 42nd International Conference on Machine Learning},
  pages={1--12},
  year={2025},
  organization={PMLR}
}
```
---
title: "Doc2hash: Learning Discrete Latent Variables for Documents Retrieval"
collection: publications
permalink: /publication/2019-naacl-doc2hash
excerpt: 'We propose Doc2hash, a novel approach for learning discrete latent representations of documents that enables efficient large-scale document retrieval.'
date: 2019-01-01
venue: 'Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL)'
paperurl: 'https://aclanthology.org/N19-1394.pdf'
citation: 'Zhang, Y., & Zhu, H. (2019). Doc2hash: Learning Discrete Latent Variables for Documents Retrieval. <i>Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics</i>.'
---

## Abstract

Document retrieval is a fundamental task in information retrieval and natural language processing. Traditional methods often rely on sparse representations like TF-IDF or dense continuous embeddings, both of which have limitations in terms of storage efficiency and retrieval speed for large-scale applications. In this paper, we propose Doc2hash, a novel approach that learns discrete latent variables for document representation, enabling efficient document retrieval through binary hash codes. Our method combines the representational power of neural language models with the efficiency of binary hashing. Doc2hash uses a variational autoencoder framework with discrete latent variables to learn compact binary representations that preserve semantic similarity between documents. We introduce a novel training objective that balances reconstruction quality with hash code diversity, ensuring that similar documents have similar hash codes while maintaining discriminative power. The discrete nature of our representations enables constant-time similarity computation and significantly reduces storage requirements. Extensive experiments on benchmark document retrieval datasets demonstrate that Doc2hash achieves competitive retrieval performance while offering substantial improvements in computational efficiency and storage costs compared to existing methods.

**Authors**: Yizhen Zhang, Hao Zhu

**Venue**: Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL) 2019

**Citations**: 25

[Download paper here](https://aclanthology.org/N19-1394.pdf)

## BibTeX Citation

```bibtex
@inproceedings{zhang2019doc2hash,
  title={Doc2hash: Learning Discrete Latent Variables for Documents Retrieval},
  author={Zhang, Yizhen and Zhu, Hao},
  booktitle={Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies},
  pages={3844--3853},
  year={2019},
  organization={Association for Computational Linguistics}
}
```
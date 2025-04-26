---
title: "Adaptive Multi-Resolution Encoding for Interactive Large-Scale Volume Visualization through Functional Approximation"
collection: publications
category: conferences
permalink: /publication/adaptive
excerpt: '**Jianxin Sun**, David Lenz, Hongfeng Yu, Tom Peterka'
date: 2024-08-31
venue: 'IEEE Symposium on Large Data Analysis and Visualization (LDAV)'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10767627'
bibtexurl:
citation:
---
**Jianxin Sun**, David Lenz, Hongfeng Yu, Tom Peterka

Abstract
======
Functional approximation as a high-order continuous representation provides a more accurate value and gradient query compared to the traditional discrete volume representation. Volume visualization directly rendered from functional approximation generates high-quality rendering results without high-order artifacts caused by trilinear interpolations. However, querying an encoded functional approximation is computationally expensive, especially when the input dataset is large, making functional approximation impractical for interactive visualization. In this paper, we proposed a novel functional approximation multi-resolution representation, Adaptive-FAM, which is lightweight and fast to query. We also design a GPU-accelerated out-of-core multi-resolution volume visualization framework that directly utilizes the Adaptive-FAM representation to generate high-quality rendering with interactive responsiveness. Our method can not only dramatically decrease the caching time, one of the main contributors to input latency, but also effectively improve the cache hit rate through prefetching. Our approach significantly outperforms the traditional function approximation method in terms of input latency while maintaining comparable rendering quality.

Bibtex
======
```bibtex
@INPROCEEDINGS{10767627,
  author={Sun, Jianxin and Lenz, David and Yu, Hongfeng and Peterka, Tom},
  booktitle={2024 IEEE 14th Symposium on Large Data Analysis and Visualization (LDAV)}, 
  title={Adaptive Multi-Resolution Encoding for Interactive Large-Scale Volume Visualization through Functional Approximation}, 
  year={2024},
  volume={},
  number={},
  pages={33-42},
  keywords={Visualization;Adaptation models;Interpolation;Three-dimensional displays;Prefetching;Rendering (computer graphics);Sampling methods;Encoding;Function approximation;Testing;functional approximation;large-scale data;multi-resolution;volume visualization},
  doi={10.1109/LDAV64567.2024.00006}
}
```

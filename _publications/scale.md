---
title: "Scalable volume visualization for big scientific data modeled by functional approximation"
collection: publications
category: conferences
permalink: /publication/scale
excerpt: '**Jianxin Sun**, David Lenz, Hongfeng Yu, Tom Peterka'
date: 2023-12-15
venue: 'IEEE International Conference on Big Data (BigData)'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10386434'
bibtexurl:
citation:
---
**Jianxin Sun**, David Lenz, Hongfeng Yu, Tom Peterka

Abstract
======
Considering the challenges posed by the space and time complexities in handling extensive scientific volumetric data, various data representations have been developed for the analysis of large-scale scientific data. Multivariate functional approximation (MFA) is an innovative data model designed to tackle substantial challenges in scientific data analysis. It computes values and derivatives with high-order accuracy throughout the spatial domain, mitigating artifacts associated with zero- or first-order interpolation. However, the slow query time through MFA makes it less suitable for interactively visualizing a large MFA model. In this work, we develop the first scalable interactive volume visualization pipeline, MFA-DVV, for the MFA model encoded from large-scale datasets. Our method achieves low input latency through distributed architecture, and its performance can be further enhanced by utilizing a compressed MFA model while still maintaining a high-quality rendering result for scientific datasets. We conduct comprehensive experiments to show that MFA-DVV can decrease the input latency and achieve superior visualization results for big scientific data compared with existing approaches.

Bibtex
======
```bibtex
@INPROCEEDINGS{10386434,
  author={Sun, Jianxin and Lenz, David and Yu, Hongfeng and Peterka, Tom},
  booktitle={2023 IEEE International Conference on Big Data (BigData)}, 
  title={Scalable Volume Visualization for Big Scientific Data Modeled by Functional Approximation}, 
  year={2023},
  volume={},
  number={},
  pages={905-914},
  keywords={Solid modeling;Interpolation;Image coding;Scalability;Pipelines;Data visualization;Computer architecture;volume visualization;functional approximation;big scientific dataset;distributed computing},
  doi={10.1109/BigData59044.2023.10386434}
}
```

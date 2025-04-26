---
title: "Rmdncache: Dual-space prefetching neural network for large-scale volume visualization"
collection: publications
category: conferences
permalink: /publication/rmdn
excerpt: '**Jianxin Sun**, Xinyan Xie, Hongfeng Yu'
date: 2024-06-05
venue: 'IEEE Transactions on Visualization and Computer Graphics (TVCG)'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10549835'
bibtexurl:
citation:
---
**Jianxin Sun**, Xinyan Xie, Hongfeng Yu

Abstract
======
Volume visualization plays a significant role in revealing important intrinsic patterns of 3D scientific datasets. However, these datasets are often large, making it challenging for interactive visualization systems to deliver a seamless user experience because of high input latency that arises from I/O bottlenecks and limited fast memory resources with high miss rates. To address this issue, we have proposed a deep learning-based prefetching method called RmdnCache, which optimizes the data flow across the memory hierarchy to reduce the input latency of large-scale volume visualization. Our approach accurately prefetches the content of the next view to fast memory using learning-based prediction while rendering the current view. The proposed deep learning architecture consists of two networks, RNN and MDN in respective spaces, which work together to predict both the location and likelihood distribution of the next view for defining an optimal prefetching range. Our method outperforms existing state-of-the-art prefetching algorithms in reducing overall input latency for visualizing real-world large-scale volumetric datasets.

Bibtex
======
```bibtex
@ARTICLE{10549835,
  author={Sun, Jianxin and Xie, Xinyan and Yu, Hongfeng},
  journal={IEEE Transactions on Visualization and Computer Graphics}, 
  title={RmdnCache: Dual-Space Prefetching Neural Network for Large-Scale Volume Visualization}, 
  year={2024},
  volume={},
  number={},
  pages={1-13},
  keywords={Prefetching;Data visualization;Rendering (computer graphics);Three-dimensional displays;Training;Data models;Deep learning;Large-scale data;volume visualization;deep learning;prefetching},
  doi={10.1109/TVCG.2024.3410091}
}
```

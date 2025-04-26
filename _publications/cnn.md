---
title: "Spatial-temporal scientific data clustering via deep convolutional neural network"
collection: publications
category: conferences
permalink: /publication/cnn
excerpt: '**Jianxin Sun**, Chunxia Wu, Yufeng Ge, Yusong Li, Hongfeng Yu'
date: 2019-12-09
venue: 'IEEE International Conference on Big Data (Big Data)'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9006507'
bibtexurl:
citation:
---
**Jianxin Sun**, Chunxia Wu, Yufeng Ge, Yusong Li, Hongfeng Yu

Abstract
======
We explore the usage of deep convolutional neural network for clustering the time steps of a spatial-temporal scientific dataset. Our approach first takes the scientific dataset as training data and trains a deep convolutional autoencoder. A low-dimensional feature space or latent space can be extracted by inferencing the encoding part of the network. As a result, each time step is transformed into a feature descriptor that can be compared with each other in the feature space. In this way, we can cluster time steps according to their feature descriptors, and each group of time steps has a similar characterization. We demonstrate the effectiveness of our approach using a real-world simulation dataset of water contamination. Multiple variables and their combinations of this dataset are fed into our approach. The trained network enables the clustering of the time steps and facilitates scientists to examine their large spatial-temporal datasets.

Bibtex
======
```bibtex
@INPROCEEDINGS{9006507,
  author={Sun, Jianxin and Wu, Chunxia and Ge, Yufeng and Li, Yusong and Yu, Hongfeng},
  booktitle={2019 IEEE International Conference on Big Data (Big Data)}, 
  title={Spatial-Temporal Scientific Data Clustering via Deep Convolutional Neural Network}, 
  year={2019},
  volume={},
  number={},
  pages={3424-3429},
  keywords={Two dimensional displays;Three-dimensional displays;Feature extraction;Training;Rendering (computer graphics);Machine learning;Convolutional neural networks;spatial-temporal scientific data;clustering;deep convolutional neural network;autoencoder;feature descriptor},
  doi={10.1109/BigData47090.2019.9006507}
}
```

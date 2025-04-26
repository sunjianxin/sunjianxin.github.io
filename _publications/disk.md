---
title: "Lm-diskann: Low memory footprint in disk-native dynamic graph-based ann indexing"
collection: publications
category: conferences
permalink: /publication/disk
excerpt: 'Yu Pan, **Jianxin Sun**, Hongfeng Yu'
date: 2023-12-15
venue: 'IEEE International Conference on Big Data (BigData)'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10386517'
bibtexurl:
citation:
---
Yu Pan, **Jianxin Sun**, Hongfeng Yu

Abstract
======
Approximate Nearest Neighbor (ANN) search has become a fundamental operation in numerous applications, including recommendation systems, computer vision, and natural language processing. The advent of Large Language Models (LLMs) arouses new interest in developing more efficient ANN algorithms, which will be the core functionality of vector databases as long-term memory of LLM. Multiple types of index structures, such as hashing-based, tree-based, and quantization-based, have been developed for ANN, and recently, graph-based algorithms have become the SOTA paradigm with the best trade-off between recall rate and query latency. However, almost all the existing graph-based index structures can only be hosted in memory due to the otherwise frequent I/O operations during searching if the graph-based index is stored on disk. The problem follows that for extremely large datasets, it is infeasible to accommodate the whole graph-based index in memory, and furthermore, it is difficult to build the whole index in memory at once. Thus, it is favorable if the graph-based index can be stored purely on disk and loaded into memory on demand during searching on the graph. There are existing efforts, such as DiskANN, which try to store graph-based index structure on disk while still keeping a compressed version of the dataset in memory to reduce disk I/O and speed up distance calculation. In this paper, we introduce LM-DiskANN, a novel dynamic graph-based ANN index that is designed specifically to be hosted on disk while keeping a low memory footprint by storing complete routing information in each node. By conducting extensive experiments on multiple benchmark datasets, we demonstrate that LM-DiskANN achieves a similar recall-latency curve while consuming much less memory compared with SOTA graph-based ANN indexes. Furthermore, its scalability and adaptability make it a promising solution for future big data applications.

Bibtex
======
```bibtex
@INPROCEEDINGS{10386517,
  author={Pan, Yu and Sun, Jianxin and Yu, Hongfeng},
  booktitle={2023 IEEE International Conference on Big Data (BigData)}, 
  title={LM-DiskANN: Low Memory Footprint in Disk-Native Dynamic Graph-Based ANN Indexing}, 
  year={2023},
  volume={},
  number={},
  pages={5987-5996},
  keywords={Technological innovation;Scalability;Memory management;Routing;Big Data applications;Search problems;Natural language processing;Approximate Nearest Neighbor;Graph Index;Memory Footprint},
  doi={10.1109/BigData59044.2023.10386517}
}
```

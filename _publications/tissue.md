---
title: "Tissue-Specific Color Encoding and GAN Synthesis for Enhanced Medical Image Generation"
collection: publications
category: conferences
permalink: /publication/tissue
excerpt: 'Yu Shi, Hannah Tang, **Jianxin Sun**, Xinyan Xie, Huijing Du, Dandan Zheng, Chi Zhang, Hongfeng Yu'
date: 2023-12-15
venue: 'IEEE International Conference on Big Data (BigData)'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10386791'
bibtexurl:
citation:
---
Yu Shi, Hannah Tang, **Jianxin Sun**, Xinyan Xie, Huijing Du, Dandan Zheng, Chi Zhang, Hongfeng Yu

Abstract
======
Medical image synthesis is important in diverse healthcare applications, such as computer-aided diagnosis, medical image analysis, and educational tools. While Generative Adversarial Networks (GANs) have shown remarkable success in generating natural images, their application to medical images often falls short in faithfully capturing essential anatomical features. In this paper, we introduce a new approach that focuses on tissue-specific color encoding to enhance medical image synthesis using GANs. Our method deviates from the conventional practice of directly training GANs on gray-scale medical images. Instead, we initiate the process by generating and encoding various gray-scale representations of distinct tissues into separate color channels within composite images. These tissue-specific color images are then utilized to train a GAN model. The GAN, once trained, excels in producing high-quality synthetic images for individual tissues, and when combined, these tissue images yield final synthesized images that better portray the intricate tissue characteristics found in medical data. We have conducted an experimental study to validate the effectiveness of our approach in comparison to alternative methods with both qualitative and quantitative assessments to evaluate the quality of synthesized individual tissues and their combined final results.

Bibtex
======
```bibtex
@INPROCEEDINGS{10386791,
  author={Shi, Yu and Tang, Hannah and Sun, Jianxin and Xie, Xinyan and Du, Huijing and Zheng, Dandan and Zhang, Chi and Yu, Hongfeng},
  booktitle={2023 IEEE International Conference on Big Data (BigData)}, 
  title={Tissue-Specific Color Encoding and GAN Synthesis for Enhanced Medical Image Generation}, 
  year={2023},
  volume={},
  number={},
  pages={4344-4349},
  keywords={Training;Image coding;Image color analysis;Image synthesis;Color;Medical services;Production;GAN;medical image synthesis;tissue-specific color encoding},
  doi={10.1109/BigData59044.2023.10386791}
}
```

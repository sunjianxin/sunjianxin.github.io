---
title: "MFA-DVR: direct volume rendering of MFA models"
collection: publications
category: conferences
permalink: /publication/mfadvr
excerpt: '**Jianxin Sun**, David Lenz, Hongfeng Yu, Tom Peterka'
date: 2024-02-01
venue: 'Journal of Visualization'
slidesurl:
paperurl: 'https://link.springer.com/article/10.1007/s12650-023-00946-y'
bibtexurl:
citation:
---
**Jianxin Sun**, David Lenz, Hongfeng Yu, Tom Peterka

Abstract
======
3D volume rendering is widely used to reveal insightful intrinsic patterns of volumetric datasets across many domains. However, the complex structures and varying scales of volumetric data can make efficiently generating high-quality volume rendering results a challenging task. Multivariate functional approximation (MFA) is a new data model that addresses some of the critical challenges: high-order evaluation of both value and derivative anywhere in the spatial domain, compact representation for large-scale volumetric data, and uniform representation of both structured and unstructured data. In this paper, we present MFA-DVR, the first direct volume rendering pipeline utilizing the MFA model, for both structured and unstructured volumetric datasets. We demonstrate improved rendering quality using MFA-DVR on both synthetic and real datasets through a comparative study. We show that MFA-DVR not only generates more faithful volume rendering than using local filters but also performs faster on high-order interpolations on structured and unstructured datasets. MFA-DVR is implemented in the existing volume rendering pipeline of the Visualization Toolkit (VTK) to be accessible by the scientific visualization community.

Bibtex
======
```bibtex
@article{sun2024mfa,
  title={MFA-DVR: direct volume rendering of MFA models},
  author={Sun, Jianxin and Lenz, David and Yu, Hongfeng and Peterka, Tom},
  journal={Journal of Visualization},
  volume={27},
  number={1},
  pages={109--126},
  year={2024},
  publisher={Springer}
}
```

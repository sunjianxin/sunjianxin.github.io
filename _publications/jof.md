---
title: "Modeling dormant fruit trees for agricultural automation"
collection: publications
category: manuscripts
permalink: /publication/jof
excerpt: 'Henry Medeiros, Donghun Kim, **Jianxin Sun**, Hariharan Seshadri, Shayan Ali Akbar, Noha M Elfiky, Johnny Park'
date: 2017-10-01
venue: 'Journal of Field Robotics'
slidesurl:
paperurl: 'https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.21679'
citation:
---
Henry Medeiros, Donghun Kim, **Jianxin Sun**, Hariharan Seshadri, Shayan Ali Akbar, Noha M Elfiky, Johnny Park

Abstract
======
Dormant pruning of fruit trees is one of the most costly and labor-intensive activities in specialty crop production. We present a system that solves the first step in the process of automated pruning: accurately measuring and modeling the fruit trees. Our system employs a laser sensor to collect observations of fruit trees from multiple perspectives, and it uses these observations to measure parameters needed for pruning. A split-and-merge clustering algorithm divides the collected data into three sets of points: trunk candidates, junction point candidates, and branches. The trunk candidates and junction point candidates are then further refined by a robust fitting algorithm that models as cylinders each segment of the trunk and primary branches. In this work, we focus on measuring the diameters of the primary branches and the trunk, which are important factors in dormant pruning and can be obtained directly from the cylindrical models. We show that the results are qualitatively satisfactory using synthetic and real data. Our experiments with three synthetic and three real apple trees of two different varieties showed that the system is able to identify the primary branches with an average accuracy of 98% and estimate their diameters with an average error of 0.6 cm. Although the current implementation of the system is too slow for large-scale practical applications (it can measure approximately two trees per hour), our study shows that the proposed approach may serve as a fundamental building block of robotic pruners in the near future.

Bibtex
======
```bibtex
@article{https://doi.org/10.1002/rob.21679,
author = {Medeiros, Henry and Kim, Donghun and Sun, Jianxin and Seshadri, Hariharan and Akbar, Shayan Ali and Elfiky, Noha M. and Park, Johnny},
title = {Modeling Dormant Fruit Trees for Agricultural Automation},
journal = {Journal of Field Robotics},
volume = {34},
number = {7},
pages = {1203-1224},
doi = {https://doi.org/10.1002/rob.21679},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.21679},
eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/rob.21679},
year = {2017}
}
```

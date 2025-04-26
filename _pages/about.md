---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Assistant Professor at the School of Computing, University of Nebraska-Lincoln. I received my Ph.D. degree in computer science from the University of Nebraska-Lincoln in 2024, advised by Professor [Hongfeng Yu](https://cse.unl.edu/~yu/). I obtained my M.S. degree in Electrical and Computer Engineering (ECE) from Purdue University, advised by Professor [Avinash Kak](https://engineering.purdue.edu/kak/). 
<!--I received my B.S degree from Harbin Institute of Technology.-->

My research concentrates on AI-driven scientific data modeling, analysis, and visualization through high-performance computing. Currently, my research work mainly focuses on sparse encoding, neural rendering, and interactive visualization.

News
======
- Dec 15, 2024: LLM-based agentic copilot for data management paper accepted by [BigData 2024](https://ieeexplore.ieee.org/abstract/document/10826038)
- Jul 26, 2024: Our [Adaptive-FAM](https://arxiv.org/abs/2409.00184) paper is accepted by LDAV 2024 - Large Data Analysis and Visualization.
- Jun 19, 2024: Our [RmdnCache](https://ieeexplore.ieee.org/abstract/document/10549835) paper is accepted by TVCG.
- Oct 27, 2023: Two papers accepted by [BigData 2023](https://bigdataieee.org/BigData2023/ImportantDates.html) as the leading author.
- Apr 02, 2023: Our [MFA-DVR](https://link.springer.com/article/10.1007/s12650-023-00946-y) paper got published in the Journal of Visualization.
- Feb 02, 2023: Please check our [review paper](https://www.sciencedirect.com/science/article/pii/S004313542300180X?casa_token=WlEPnkdR5akAAAAA:kjxbRnqBaa8vDkgmDDFCv-UxDjXrSMhSQwXlkNmzKaKFGphWdj30-e7-mJxswjyAzIzbMPyS) on Machine Learning in the Groundwater domain.

Recent Selected Publications
------
- Adaptive Multi-Resolution Encoding for Interactive Large-Scale Volume Visualization through Functional Approximation
  Jianxin Sun, David Lenz, Hongfeng Yu, Tom Peterka
  IEEE Symposium on Large Data Analysis and Visualization (LDAV), 2024

- Adaptive Multi-Resolution Encoding for Interactive Large-Scale Volume Visualization through Functional Approximation
  Jianxin Sun, David Lenz, Hongfeng Yu, Tom Peterka
  IEEE Symposium on Large Data Analysis and Visualization (LDAV), 2024

<img src="https://ucomm.unl.edu/sites/unl.edu.university-communication/files/styles/no_crop_1920/public/media/image/nebraska-n.jpg?itok=sUuW-xG5" alt="Square Image" style="width: 50px; height: 50px; object-fit: cover; margin-right: 20px;"/>
  <div>
    Your text goes here. You can include multiple paragraphs or other markdown elements.
    Just make sure they're properly indented within this div.
  </div>
</div>

The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

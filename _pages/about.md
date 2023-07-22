---
permalink: /
title: "About me - 周子淇 / Ziqi Zhou"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

Education
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Research Interests
======
My research focuses on providing fundamental understandings of how Federated Learning (FL) is influenced by system-level variability in the computing infrastructure, and statistical variability in the training data, under adversarial settings. Inspired by the theoretical or experimental insights, I seek to design system- and data-aware distributed/federated training algorithms that are byzantine-robust and superior in generalization performance. In the future, I am committed to improving distributed/federated training algorithms that can seamlessly scale to a large number of computing nodes in realistic scenarios in terms of byzantine robustness, privacy preserving, communication/computation efficiency, and generalization performance.

I am broadly interested in federated learning, algorithm robustness, distributed optimization, and medical image analysis.

Publication & Manuscripts
------
- Shielding Federated Learning: Rectifying Direction Is All You Need 
**Jianrong Lu**; Shengshan Hu; Wei Wan; Minghui Li; Leo Yu Zhang; Xiaojing Ma; Hai Jin 
NDSS 2023, UNDER REVIEW (passed the first round of review): The Network and Distributed System Security Symposium (NDSS), 2023 

- BadHash: Invisible Backdoor Attacks against Deep Hashing with Clean Label. [[Code]](https://github.com/CGCL-codes/BadHash)[[pdf]](https://dl.acm.org/doi/abs/10.1145/3503161.3548272).
Shengshan Hu, **Ziqi Zhou**, Yechao Zhang, Leo Yu Zhang, Yifeng Zheng, Yuanyuan He, Hai Jin.
Proceedings of the 30th ACM International Conference on Multimedia  (*ACM MM 2022*).  


Honors & Awards
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 



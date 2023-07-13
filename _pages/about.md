<!-- ---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->


---
permalink: /
title: "Jiahua Huang 黄嘉华"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Research Interest
I am interested in <u>edge computing</u> and <u>resource management</u>, with a special focus on <u>AI/GPU cluster management</u> with <u>machine learning</u> techniques.


## Education
<img src="../images/SCUT.png"
     alt="SCUT"
     style="float: left; margin-right: 10px; height: 50px; width:50px;"/>

**South China University of Technology, Guangzhou, China**
- Eng.D. in [Computer Science](http://www2.scut.edu.cn/ft/), advised by [Prof. Weiwei Ling](http://www2.scut.edu.cn/cs/2017/0629/c22284a328098/page.htm), Sep. 2023 -- Present

<img src="../images/siat.jpg"
     alt="SCUT"
     style="float: left; margin-right: 10px; height: 50px; width:50px;"/>

**Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, Shenzhen, China**
- Master of Engineering, [Electronic Information](https://www.siat.ac.cn/), advised by [Prof. Yang Wang](https://teacher.ucas.ac.cn/~yangwang), Sep. 2020 -- Jun. 2023

<img src="../images/jnu.jpeg"
     alt="SCUT"
     style="float: left; margin-right: 10px; height: 50px; width:50px;"/>

**JiangNan University, Wuxi, China**
- Bachelor of Engineering, [Digital Media Technology](http://ai.jiangnan.edu.cn/), Sep. 2015 -- Jun. 2019


## Publications

- [**[ATC \'23]**](https://www.usenix.org/conference/atc23/) **Beware of Fragmentation: Scheduling GPU-Sharing Workloads with Fragmentation Gradient Descent** [[paper]](./files/2023.ATC-FGD-Weng.pdf) [[slides]](./files/2023.ATC-FGD--slides.pdf) [[data]](https://github.com/alibaba/clusterdata/tree/master/cluster-trace-gpu-v2023) [[code]](https://github.com/hkust-adsl/kubernetes-scheduler-simulator) [[url]](https://www.usenix.org/conference/atc23/presentation/weng) [[bibtex]](./files/2023.ATC-FGD-Weng.txt)
  - **Qizhen Weng\***, Lingyun Yang\* (co-first author), Yinghao Yu, Wei Wang, Xiaochuan Tang, Guodong Yang, and Liping Zhang
  - in the Proceedings of the 2023 USENIX Annual Technical Conference, Boston, MA, July 2023.

- [**[NSDI \'22]**](https://www.usenix.org/conference/nsdi22/) **MLaaS in the Wild: Workload Analysis and Scheduling in Large-Scale Heterogeneous GPU Clusters** [[paper]](./files/2022.NSDI-MLaaS-Weng.pdf) [[slides]](./files/2022.NSDI-MLaaS-Weng-slides.pdf) [[data]](https://github.com/alibaba/clusterdata/tree/master/cluster-trace-gpu-v2020) [[code]](https://github.com/alibaba/clusterdata/tree/master/cluster-trace-gpu-v2020/simulator) [[url]](https://www.usenix.org/conference/nsdi22/presentation/weng) [[bibtex]](./files/2022.NSDI-MLaaS-Weng.txt)
  - **Qizhen Weng**, Wencong Xiao, Yinghao Yu, Wei Wang, Cheng Wang, Jian He, Yong Li, Liping Zhang, Wei Lin, and Yu Ding
  - in the Proceedings of the 19th USENIX Symposium on Networked Systems Design and Implementation, Renton, WA, April 2022.

- [**[SoCC \'22]**](https://acmsocc.github.io/2022/) **Workload Consolidation in Alibaba Clusters: The Good, the Bad, and the Ugly** [[paper]](./files/2022.SoCC-Alibaba-Zhang.pdf) [[slides]](./files/2022.SoCC-Alibaba-Zhang-slides.pdf) [[url]](https://dl.acm.org/doi/10.1145/3542929.3563465) [[bibtex]](./files/2022.SoCC-Alibaba-Zhang.txt)
  - Yongkang Zhang, Yinghao Yu, Wei Wang, Qiukai Chen, Jie Wu, Zuowei Zhang, Jiang Zhong, Tianchen Ding, **Qizhen Weng**, Lingyun Yang, Cheng Wang, Jian He, Guodong Yang, and Liping Zhang
  - in the Proceedings of ACM Symposium on Cloud Computing, San Francisco, CA, November 2022.

- [**[TCC \'21]**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6245519) **Accelerating Distributed Learning in Non-Dedicated Environments** [[paper]](./files/2021.TCC-LBBSP-Chen.pdf) [[url]](https://ieeexplore.ieee.org/document/9508170) [[bibtex]](./files/2021.TCC-LBBSP-Chen.txt)
  - Chen Chen, **Qizhen Weng**, Wei Wang, Baochun Li, and Bo Li,
  - in IEEE Transactions on Cloud Computing, July 2021.

- [**[SC \'20]**](https://sc20.supercomputing.org/) **Metis: Learning to Schedule Long-Running Applications in Shared Container Clusters at Scale** [[paper]](./files/2020.SC-Metis-Wang_Weng.pdf) [[slides]](./files/2020.SC-Metis-Wang_Weng-slides.pdf) [[code]](https://github.com/lwangbm/Metis) [[url]](https://ieeexplore.ieee.org/document/9355246) [[bibtex]](./files/2020.SC-Metis-Wang_Weng.txt)
  - Luping Wang\*, **Qizhen Weng\* (co-first author)**, Wei Wang, Chen Chen, and Bo Li
  - in the Proceedings of IEEE/ACM International Conference for High Performance Computing, Networking, Storage, and Analysis, Atlanta, GA, November 2020. 

- [**[SoCC \'20]**](https://acmsocc.github.io/2020/) **Semi-Dynamic Load Balancing: Efficient Distributed Learning in Non-Dedicated Environments** [[paper]](./files/2020.SoCC-LBBSP-Chen.pdf) [[url]](https://dl.acm.org/doi/10.1145/3419111.3421299) [[bibtex]](./files/2020.SoCC-LBBSP-Chen.txt)
  - Chen Chen, **Qizhen Weng**, Wei Wang, Baochun Li, and Bo Li
  - in the Proceedings of ACM Symposium on Cloud Computing, Renton, WA, October 2020.

- [**[APSys \'19]**](https://icsr.zju.edu.cn/apsys2019/) **Towards Framework-Independent, Non-Intrusive Performance Characterization for Dataflow Computation** [[paper]](./files/2019.ApSys-Perf-Tian.pdf) [[url]](https://dl.acm.org/doi/abs/10.1145/3343737.3343743) [[bibtex]](./files/2019.ApSys-Perf-Tian.txt)
  - Huangshi Tian, **Qizhen Weng**, and Wei Wang
  - in the Proceedings of ACM SIGOPS Asia-Pacific Workshop on Systems, Hangzhou, China, August 2019.

<!--
- **Cloud Management with Reinforcement Learning** [[paper]](./files/2019.Survey-Cloud_Mgmt_w_RL-Weng.pdf) [[slides]](./files/2019.Survey-Cloud_Mgmt_w_RL-Weng-slides.pdf) [[bibtex]](./files/2019.Survey-Cloud_Mgmt_w_RL-Weng.txt)
  - **Qizhen Weng**
  - survey paper for the Ph.D. Qualification Exam (PQE), CSE, HKUST, Hong Kong SAR, China, May 2019.
-->

- [**[SoCC \'18]**](https://acmsocc.github.io/2018/) **Fast Distributed Deep Learning via Worker-adaptive Batch Sizing** [[paper]](./files/2018.SoCC-LBBSP-Chen.pdf) [[url]](https://dl.acm.org/doi/abs/10.1145/3267809.3275463) [[bibtex]](./files/2018.SoCC-LBBSP-Chen.txt)
  - Chen Chen, **Qizhen Weng**, Wei Wang, Baochun Li, and Bo Li
  - poster paper in the Proceedings of ACM Symposium on Cloud Computing, Carlsbad, CA, October 2018.

- [**[ICDCS \'18]**](https://icdcs2018.ocg.at/) **OpuS: Fair and Efficient Cache Sharing for In-Memory Data Analytics** [[paper]](./files/2018.ICDCS-OpuS-Yu.pdf) [[url]](https://ieeexplore.ieee.org/abstract/document/8416288/) [[bibtex]](./files/2018.ICDCS-OpuS-Yu.txt)
  - Yinghao Yu, Wei Wang, Jun Zhang, **Qizhen Weng**, and Khaled B. Letaief
  - in the Proceedings of IEEE International Conference on Distributed Computing Systems, Vienna, Austria, July 2018.

- **Phishing Wi-Fi detection method** [[paper]](./files/2016.CNPatent-Phishing-CN106330935B-Hua.pdf) [[url]](https://epub.cnipa.gov.cn/patent/CN106330935B) [[bibtex]](files/2016.CNPatent-Phishing-CN106330935B-Hua.txt)
  - Cunqing Hua, **Qizhen Weng**, Weixin Li, Zhaohui Jiang, and Kun Yang
  - CN106330935B, China National Intellectual Property Administration, Aug 2016.


## Experiences
**[Shanghai AI Laboratory](https://shlab.org.cn), Shanghai**
- System Researcher, Nov. 2022 -- Present

**Alibaba Group, Hangzhou**
- Research Intern, Oct. 2021 -- Oct. 2022

**Alibaba Cloud, Hangzhou**
- Research Intern, Jun. 2020 -- Sep. 2021

**COMP4651: Cloud Computing and Big Data Systems, HKUST, HKSAR**
- Teaching Assistant, Fall 2018, Fall 2019

**SAP, Shanghai**
- IT Support Intern, Jun. 2016 -- Dec. 2016


## Awards and Fellowships
**[Hong Kong Ph.D. Fellowship Award](https://cerg1.ugc.edu.hk/hkpfs/index.html)**
- Research Grants Council (RGC) of Hong Kong, 2017 -- 2020

**[Shanghai Outstanding Graduates (1%)](http://xsb.seiee.sjtu.edu.cn/xsb/info/12484.htm)**
- Shanghai Municipal Education Commission, 2017

**[Cyber-Security Scholarship](http://www.cidf.net/2016-05/20/c_1118905072.htm)**
- China Internet Development Foundation (CIDF), 2016
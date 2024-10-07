---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Ph.D student, Vehicle Operation Engineering, [School of Automobile, Chang’an University](https://www.chd.edu.cn/). My supervisor is [Prof. Shifeng NIU](https://js.chd.edu.cn/qcxy/nsf/list.htm). I recived my Master’s Degree in [School of Automobile & Transportation , Xihua University](https://qc.xhu.edu.cn/), supervised by [Prof. Daowen ZHANG](https://teacher.xhu.edu.cn/qcyjt/zdw/list.psp), and recived my Bachelor’s Degree in [Automotive Service Engineering, Chengdu Normal University](https://www.cdnu.edu.cn/wlgcxy/index/lgxw.htm).
My research interest includes *Big Data Mining, Automotive Active and Passive Safety Technology,  Reconstruction and Evaluation of Automatic Driving Test Scenarios*. The research progress focuses on **data-driven traffic accident risk identification and collaborative control, vehicle crash safety and human injury biomechanics**.

You can find my CV here: [MiN.L's Curriculum Vitae](../assets/Curriculum_Vitae.pdf).


Education
======
■ Sep 2024- Present, Vehicle Operation Engineering / Ph.D./ Chang’an University, Xi An.

■ Sep 2021-Jun 2024,  Transportation / M.E./ Xihua University, Cheng Du.                                 

■ Sep 2017-Jun 2021, Automotive Service Engineering / B.E./ Chengdu Normal University, Cheng Du.       


Publications
======
**M, Li.**, D, Zhang., Q, Liu., & T, Zhang. (2023). Driver injury from vehicle side impacts when automatic emergency braking and active seat belts are used. Sensors, 23(13), 5821. https://doi.org/10.3390/s23135821

D, Zhang., **M, Li.**, S, Pang., & Q, Luo. (2023). Accident causes and its topological hierarchy analysis for heavy-duty trucks and two-wheelers. Journal Automotive Safety and Energy, 14(02), 157-164. doi: 10.3969/j.issn.1674-8484.2023.02.002

P, Li., C, Zhao., **M, Li.**, D, Zhang., Q, Luo., C,. Zhang, & W, Hu. (2024). Analysis of pedestrian accident severity by considering temporal instability and heterogeneity. Heliyon, 10(11), e32013. https://doi.org/10.1016/j.heliyon.2024.e32013

Scholarly and Competitive Activities
======
2023 "Huashu Cup" International Mathematical Contest in Modeling [Meritorious]()
2022 Asia and Pacific Mathematical Contest in Modeling [First Prize Postgraduate Group](../assets/2204079_1APMCM.pdf)
2022 ShuWei Cup IMCM [Meritorious]()
2022 Attending (ITSAC 2022)[], Chengdu



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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

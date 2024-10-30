---
permalink: /
title: "Personal Experience"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a doctoral student majoring in Computer Science. Currently, I am enrolled at Henan University, where my master's advisor was Professor Xianyu Zuo and my doctoral advisor is Professor Lei Zhang. My research interests primarily focus on unsupervised feature selection, clustering, and privacy computing.

**Throughout my academic career, I have participated in several projects, including but not limited to:**

[1]. **National Civil Space Infrastructure Common Technology Support Project**: This project is a key support project of the Twelfth Five-Year Plan, aimed at addressing the common application support needs of nine land observation satellites launched during the Twelfth Five-Year Plan period and beyond, improving the quantitative application level of remote sensing satellites, establishing a national civil space infrastructure common application support platform, and creating a comprehensive service platform for collecting six types of ground truth data.

[2]. **High-resolution Earth System Scientific Research Demonstration Project**: This is a national major special project where Henan University is mainly responsible for three sub-system modules: "Demonstration Subsystem for the Response of Qinghai-Tibet Plateau to Climate Change," "Demonstration Subsystem for Ecosystem Changes in the Loess Plateau," and "Demonstration Subsystem for Disaster Emergency Monitoring in Tibet.

[3]. **Hainan Dianan Smart Internet Management Service Platform**: This project was commissioned by Henan Yunsihui Education Technology Co., Ltd. to Henan University for the development of an intelligent English online learning system. Based on the assessment of students' vocabulary and problem-solving abilities, it dynamically adjusts students' learning levels through a learning ability model, thereby accurately grasping students' learning situations and pushing corresponding learning content.

[4]. **Optimization Study of Train Operation Schedules Based on Passenger Demand for Urban Rail Transit Services**: This project was commissioned by Casco Signal (Zhengzhou) Co., Ltd. to Henan University for research on train operation schedules. By studying the characteristics of urban rail transit passenger flow changes, modeling and analyzing large amounts of historical passenger flow data and concurrent scheduling arrangements, it aims to achieve optimal capacity matching with passenger flow under resource and constraint conditions, i.e., the optimal train schedule.

[5]. **Construction and Application of Adaptive Sparse Learning Models for High-dimensional Data**: This project focuses on high-dimensional adaptive structural sparse feature selection models derived from high-dimensional data analysis in face recognition and biomedicine. Its significance lies in effectively addressing the analysis problems of large-scale high-dimensional data with correlated feature structures in practical applications, providing a rich theoretical foundation for high-dimensional feature selection, and having important application value in areas such as face recognition, gene selection, cancer treatment, and diagnosis.

**Academic Publications:**

[1] Y. Wang, W. Zhang, X. Zuo*, and B. Jiang, “Regression with adaptive lasso and correlation based penalty,” Applied Mathematical Modelling, vol. 105, pp. 179–196, 2022. (SCI-1, Top)

[2] X. Zuo, X. Wang, W. Zhang, Y. Wang, “MISPSO-Attack: An efficient adversarial watermarking attack based on multiple initial solution particle swarm optimization,” Applied Soft Computing, 2023, 10777, ISSN 1568-4946. (SCI-1)


If you are interested in my research or would like to discuss related topics, feel free to contact me via email at zhangwenbo@henu.edu.cn. I am also very open to invitations for collaboration opportunities or academic exchanges. Thank you for visiting, and I hope my research can contribute to advancements in this field. I look forward to exploring future developments together with fellow professionals and enthusiasts.


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
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

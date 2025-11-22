---
permalink: /
title: "Haobo Fang 方浩博"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi! I’m Haobo Fang, a fourth-year undergraduate in the Electrical and Computer Engineering Department at the University of Michigan, where I am fortunate to be advised by [Prof. Xiaonan (Sean) Huang](https://robotics.umich.edu/people/faculty/xiaonan-sean-huang/) in the [Hybrid Dynamic Robotics Lab](https://soft.robotics.umich.edu/). My research focuses on developing scalable, adaptable, and reliable robots for human interaction in everyday activities. I explore origami-inspired soft robotic arms, bio-inspired systems, advanced control methods, and intelligent manufacturing through continual learning. I am also pursuing a bachelor’s degree in Mechanical Engineering at Shanghai Jiao Tong University, where I have had the honor of working with [Prof. Youyi Bi](https://www.ji.sjtu.edu.cn/about/faculty-staff/faculty-directory/faculty-detail/24/) in the [Data-informed Design and Intelligent Systems Lab](https://sites.gc.sjtu.edu.cn/youyibi/people/).

# Publications

{% if site.publication_category %}
{% for category in site.publication_category  %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}
{% continue %}
{% endif %}
{% include archive-mainpage.html %}
{% endfor %}
{% endfor %}
{% endif %}

# CV

Feel free to download my CV [here](/files/Resume_Haobo_Fang.pdf) or visit the CV tag.

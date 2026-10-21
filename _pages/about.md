---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Sirui (Eric) Chen (陈思睿), a final-year CS PhD student at Stanford advised by Professor [Karen Liu](https://tml.stanford.edu/people/karen-liu). I am interested in designing robot control and planning algorithms for contact-rich tasks such as dexterous manipulation and humanoid whole-body loco-manipulation. I also work on solving complex control problems on real robots by combining human demonstrations from different sources with analytical modeling.

I interned at Honda Research Institute in summer 2024, advised by [Rana Soltani Zarrin](https://scholar.google.com/citations?user=7NGxvsgAAAAJ&hl=en); at NVIDIA GEAR Lab in summer and fall 2025, advised by [Yuke Zhu](https://yukezhu.me/) and [Zhengyi Luo](https://www.zhengyiluo.com/); and at Amazon FAR in 2026, advised by Karen Liu and [Guanya Shi](https://www.gshi.me/).

In my free time, I enjoy photography and hiking; [here](https://500px.com/p/ericcsr?view=photos) are some photos I have taken. Feel free to reach out about full-time opportunities or to discuss research ideas.

## Publications

{% include base_path %}
{% assign publications = site.publications | sort: "date" | reverse %}
{% for post in publications limit: 4 %}
  {% include archive-single.html %}
{% endfor %}

[All publications]({{ base_path }}/publications/)
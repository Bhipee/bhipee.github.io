---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes/intro.md %}

<!-- {% include_relative includes/news.md %} -->

{% include_relative includes/pub.md %}

{% include_relative includes/honers.md %}

{% include_relative includes/edu.md %}


<!-- # 💬 Invited Talks
- *2021.06*, Visual intelligence for enhanced perception, Huawei internal talk
- *2021.06*, Digital Image Processing, Beihang international class
- *2020.06*, Deep learning interpretability, Meituan internal talk -->

# 💻 Work Experience & Internship
- *2025.07 - present*, RA@[PolyU/InfiX.ai](https://huggingface.co/InfiX-ai), Hong Kong, China.
- *2025.01 - 2025.06*, Intern@[ByteDance](https://www.bytedance.com/cn), Pico, Beijing, China.
- *2023.07 - 2023.09*, Intern@[Tsinghua University](https://www.idea.edu.cn), School of Vehicle and Mobility, Beijing, China.

<center> <i><font color=Gray>Last updated on Aug. 2025</font></i> </center>
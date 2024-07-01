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

I am currently a second-year Master's student at Peking University, under the guidance of [Professor Houfeng Wang](https://scholar.google.com/citations?hl=en&user=YCX4y1gAAAAJ&view_op=list_works&sortby=pubdate). My research interests lie in large language models and reinforcement learning.

I completed my undergraduate studies at the School of Computer Science, Wuhan University, from March 2019 to June 2022. Before that, I studied at the School of Urban Design at the same university from September 2018 to March 2019.

In terms of professional experience, I have interned at two renowned organizations. From April to July 2023, I interned at Zhihu, China, where I was involved in evaluating the mathematics, common sense, and reasoning capabilities of large language models.

Currently, from August 2023 to September 2024, I am interning at Microsoft in the [Data Knowledge and Intelligence Group (DKI)](https://www.microsoft.com/en-us/research/group/data-knowledge-intelligence/) in Beijing. Here, I am focusing on fine-tuning large language models for specific tasks on tabular data.

{% include_relative includes/pub.md %}


# 📖 Educations

- *2022.09 - 2025.06 (now)*, Master, Peking University, Beijing.
- *2019.03 - 2022.06*, Undergraduate, School of Computer Science, Wuhan University, Wuhan. 
- *2018.09 - 2019.03*, Undergraduate, School of Urban Design, Wuhan University, Wuhan. 

# 💻 Internships

- *2023.08 - 2024.09(now)*, Microsoft, [Data Knowledge and Intelligence Group(DKI)](https://www.microsoft.com/en-us/research/group/data-knowledge-intelligence/), Beijing.
- *2023.04 - 2023.07*, Zhihu, China.

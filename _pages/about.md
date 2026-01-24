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

I’m a Master Student studying at Shanghai Jiao Tong University, major in Computer Science.  
I'm a student at the [RHOS Lab](https://mvig-rhos.com/), Shanghai Jiao Tong University, under the supervision of Prof. [Yong-Lu Li](https://dirtyharrylyl.github.io/).

My research interests mainly lie in Data Attribution and Robotics.

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Our paper on [efficient dataset distillation](https://arxiv.org/abs/2305.18381) is accepted to **ECCV 2024**.
- *2024.02*: &nbsp;🎉🎉 Our paper on [video distillation](https://arxiv.org/abs/2312.00362) is accepted to **CVPR 2024**.

# 📝 Publications 
equal contribution: *  
corresponding author: #
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/video_distill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dancing with Still Images: Video Distillation via Static-Dynamic Disentanglement](https://arxiv.org/abs/2312.00362)

**Ziyu Wang**\*, Yue Xu\*, Cewu Lu, Yong-Lu Li#

[**Project**](https://github.com/yuz1wan/video_distillation)  ![Stars](https://img.shields.io/github/stars/yuz1wan/video_distillation?color=yellow&label=Stars)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this work, we provide the first systematic study of video distillation and introduce a taxonomy to categorize temporal compression.
- We introduce a novel taxonomy for temporal condensation in video distillation methods, which guides our and future works.
- We propose a novel paradigm, enabling existing image distillation techniques to achieve improved results when applied to video distillation while using an even smaller memory storage budget. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/distill_pruning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distill Gold from Massive Ores: Efficient Dataset Distillation via Critical Samples Selection](https://arxiv.org/abs/2305.18381)

Yue Xu, Yong-Lu Li#, Kaitong Cui, **Ziyu Wang**, Cewu Lu, Yu-Wing Tai, Chi-Keung Tang

[**Project**](https://github.com/silicx/GoldFromOres)  ![Stars](https://img.shields.io/github/stars/silicx/GoldFromOres?color=yellow&label=Stars)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This is the very first work that systematically study the data redundancy in the dataset distillation. 
- We propose multiple effective criteria for pruning, and we hope our observation, analysis and empirical results could provide deeper insight into the internal mechanism of dataset distillation and neural network training.
</div>
</div>

<!-- # 🎖 Honors and Awards
<!-- 校优秀毕业生 -->
<!-- - *2025.06* **Shanghai Jiao Tong University Outstanding Graduate**.
- *2024.07* **China College IC Competition** East China Division First Prize.
- *2024.06* **Shanghai's Hope Star of Tomorrow's Technology** (Only 100 groups of undergraduate, master's, and doctoral students in Shanghai). -->
<!-- - *2023.10* **China Optics Valley Scholarship - Optoelectronic Information Award** (No more than 30 undergraduate students in SJTU). -->
<!-- - *2023.10* Zhiyuan Honors Scholarship (top 5%).
- *2022.10* Zhiyuan Honors Scholarship (top 5%). -->

# 📖 Educations
- *2025.09 - 2028.03 (expected)*, M.S. major in Computer Science, Shanghai Jiao Tong University
- *2021.09 - 2025.06*, B.S. major in Micro Electronics, Shanghai Jiao Tong University
  - **Zhiyuan Honor Program of Engineering** (an elite program for Top 5% talented students)

# 💻 Internships
- *2023.02 - Present*, [RHOS Lab](https://mvig-rhos.com/), China. Instructor: Yong-Lu Li.
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

I am a Ph.D. student at [Peking University](https://www.pku.edu.cn/), advised by Prof. [Peng-Shuai Wang](https://wang-ps.github.io/). I received my B.S. degree from the School of Electronics Engineering and Computer Science at Peking University in 2024.

My research interests lie in **3D Generation** and **Computer Graphics**, with a focus on developing efficient representations and generative models for high-quality 3D shape synthesis.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2025</div><img src='images/octgpt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OctGPT: Octree-based Multiscale Autoregressive Models for 3D Shape Generation](https://arxiv.org/abs/2504.09975)

**Si-Tong Wei**, Rui-Huan Wang, Chuan-Zhi Zhou, Baoquan Chen, Peng-Shuai Wang

[**arXiv**](https://arxiv.org/abs/2504.09975) \| [**Code**](https://github.com/octree-nn/octgpt)

A novel multiscale autoregressive model for 3D shape generation that improves the efficiency and performance of prior 3D autoregressive approaches.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SGP 2025</div><img src='images/octfusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OctFusion: Octree-based Diffusion Models for 3D Shape Generation](https://arxiv.org/abs/2408.14732)

Bojun Xiong, **Si-Tong Wei**, Xin-Yang Zheng, Yan-Pei Cao, Zhouhui Lian, Peng-Shuai Wang

*Computer Graphics Forum (Symposium on Geometry Processing), 2025*

[**arXiv**](https://arxiv.org/abs/2408.14732) \| [**Code**](https://github.com/octree-nn/octfusion)

An octree-based diffusion model that generates high-quality 3D shapes with arbitrary resolutions in 2.5 seconds on a single GPU.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SGP 2025</div><img src='images/octfusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Masked Retraining Teacher-Student Framework for Domain Adaptive Object Detection](http://openaccess.thecvf.com/content/ICCV2023/html/Zhao_Masked_Retraining_Teacher-Student_Framework_for_Domain_Adaptive_Object_Detection_ICCV_2023_paper.html), Zijing Zhao, **Sitong Wei**, Qingchao Chen, Dehui Li, Yifan Yang, Yuxin Peng, Yang Liu
**ICCV 2023** 
[**Paper**](http://openaccess.thecvf.com/content/ICCV2023/html/Zhao_Masked_Retraining_Teacher-Student_Framework_for_Domain_Adaptive_Object_Detection_ICCV_2023_paper.html) \| [**Code**](https://github.com/JeremyZhao1998/MRT-release)
</div>
</div>

# 📖 Educations
- *2024 - Present*, Ph.D. Student, Peking University
  - Advisor: Prof. [Peng-Shuai Wang](https://wang-ps.github.io/)
  - Research: 3D Generation and Computer Graphics
- *2020 - 2024*, B.S., School of Electronics Engineering and Computer Science, Peking University


# 💼 Services
- **Reviewer**: CVPR 2026, TOG
- **Teaching Assistant**:
  - Computer Vision (2023, 2024, 2025)
  - Frontiers in Geometric Computing (2024, 2026)
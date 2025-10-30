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
  
I am Rui Qian, a Master's student in Computer Control and Automation at Nanyang Technological University (NTU), Singapore, supervised by **Prof. Lihua Xie**. My research lies at the intersection of **3D Computer Vision** and **Robotic Perception**, with a particular focus on **semantic scene understanding**, **3D Gaussian representations**, and **efficient spatial intelligence**. I am broadly interested in enabling embodied agents to perceive, reconstruct, and interact with the real world through scalable and data-efficient 3D learning.

My long-term goal is to bridge geometric perception and semantic reasoning toward building generalizable 3D world models for robotics and autonomous systems. .


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
 
# 📝 Publications
{% include publications/lunarplan_icra2026/index.html %}
{% include publications/starc_icra2026/index.html %}
{% include publications/splatssc_aaai26/index.html %} 

# 📜 Patents
{% include patents/index.html %}

# 🚀 Projects
## 💼 Professional Projects
{% include projects/Aibot/index.html %}
{% include projects/XINCHI/index.html %}
{% include projects/CHIJI/index.html %}
## 🎨 Toy Projects
{% include projects/Toy/index.html %}
 
# 🎖 Honors and Awards
{% include awards/index.html %}
 
# 📖 Educations 
- *2020.06 - 2024.06*, Changzhou University, Changzhou, China, Bachelor of ElectronicInformation Engineering. 
- *2024.08 - 2025.10 (now)*, Nanyang Technological University, Singapore, Master of Computer Control and Automation. 

# 🗺️ Visitor Map
<details style="margin:20px 0;">
  <summary style="cursor:pointer; padding:10px; background:#f0f0f0; border-radius:5px; font-weight:600;">
    Click to view visitor map 🌍
  </summary>
  <div style="text-align:center; margin:20px 0;">
    <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=e3Ce3OtibDpE3LEi5P9_ogmq3Dt5rZA_atT8pzf0DGw&cl=ffffff&w=a"></script>
  </div>
</details>

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
 
# 🧭 About Me 

Hello! I am Rui Qian, a Master's student in Computer Control and Automation at Nanyang Technological University (NTU), Singapore, supervised by **Prof. Lihua Xie**.

My research interests lie at the intersection of **3D Computer Vision** and **Robotic Perception**. My core academic ambition is to advance machine spatial intelligence, focusing on how autonomous agents can perceive, comprehend, and interact with our complex and dynamic 3D world in a manner akin to humans.
  
I am particularly interested in **semantic scene understanding** and developing advanced scalable 3D representation methods, such as the involving 3D Gaussian representations. I believe that true autonomy hinges on a machine's ability to reconstruct (geometry) and understand (semantics) a persistent internal model of its environment. 

In the long term, I aim to bridge geometric perception and semantic reasoning. I am passionate about developing foundation models for 3D world understanding to empower future robotic and Embodied AI systems. My goal is to enable these agents with higher-level reasoning capabilities, allowing them to build persistent, high-fidelity digital twins of their environment and ultimately, to seamlessly connect the physical and virtual worlds. 

# 🔥 News
- *2025.9*: &nbsp; Expect to graduate from NTU in December 2025. Pursuing a **PhD** or **Research Assistantship** currently!
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.--> 

# 📝 Publications
{% include publications/splatssc_aaai26/index.html %} 
{% include publications/lunarplan_icra2026/index.html %}
{% include publications/starc_icra2026/index.html %}
 
{% comment %}
## 🎨 Toy Projects 
{% include projects/Toy/index.html %}
{% endcomment %}
 
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

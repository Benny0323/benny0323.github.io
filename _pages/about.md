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
# 😉 About Me
I am currently pursuing my master’s degree at the Laboratory of Image Science and Technology, School of Computer Science and Engineering, [Southeast University](https://www.seu.edu.cn), Nanjing, specializing in Deep Learning-Based CT Metal Artifact Reduction under the supervision of [Prof. Yikun Zhang](https://cs.seu.edu.cn/yikun/). I have a broad interest in deep learning models, particularly in Medical Image Analysis and Generative AI Models, and I am also an enthusiastic self-learner with diverse interests in computer science.

📫 How to contact me: [220252325@seu.edu.cn](220252325@seu.edu.cn).

<!-- === CV Download Module === -->
{% assign cv_path = "/assets/东南大学_陈章昊_计算机技术.pdf" %}
{% assign cv_file = site.static_files | where: "path", cv_path | first %}

<div class="cv-download">
  <a class="cv-btn" href="{{ cv_path | relative_url }}" target="_blank" rel="noopener" download>
    📄 Download My Chinese CV
  </a>
  {% if cv_file %}
    <div class="cv-meta">
      <span>Last updated：{{ cv_file.modified_time | date: "%Y-%m-%d" }}</span>
      <span> · Size: 389 KB</span>
    </div>
  {% endif %}
</div>

<style>
  .cv-download { margin: 12px 0 20px; }
  .cv-btn {
    display: inline-block;
    padding: 8px 14px;
    border-radius: 8px;
    background: #2b6cb0;
    color: #fff !important;
    text-decoration: none;
    font-weight: 500;
    transition: transform .06s ease-in-out, opacity .2s ease-in-out;
  }
  .cv-btn:hover { transform: translateY(-1px); opacity: .95; }
  .cv-meta {
    margin-top: 4px;
    font-size: 0.8em;
    color: #555;
  }
</style>
<!-- === /CV Download Module === -->

<img alt="GitHub User's stars" src="https://img.shields.io/github/stars/benny0323">
<img alt="GitHub followers" src="https://img.shields.io/github/followers/benny0323">


<div class='photo-box'>
  <div class='photo-box-image'><div><img src='images/p/1.jpg' alt="sym" width="300" height="220"></div></div>
  <div class='photo-box-image'><div><img src='images/p/2.jpg' alt="sym" width="300" height="220"></div></div>
  <div class='photo-box-image'><div><img src='images/p/3.jpg' alt="sym" width="300" height="220"></div></div>
  <div class='photo-box-image'><div><img src='images/p/4.jpg' alt="sym" width="300" height="220"></div></div>
  <div class='photo-box-image'><div><img src='images/p/5.jpg' alt="sym" width="300" height="220"></div></div>
  <div class='photo-box-image'><div><img src='images/p/6.jpg' alt="sym" width="300" height="220"></div></div>
</div>



# 📖 Educations
- *2021.09 - 2025.06*, Undergraduate student (Double Degree): Computer Science and Technology, [Hangzhou Dianzi University](https://www.hdu.edu.cn), Hangzhou, China
- *2021.09 - 2025.06*, Undergraduate student (Double Degree): Informatics and Computer Engineering, [ITMO University](https://itmo.ru), Saint Petersburg, Russia
- *2025.09 - Now*, Master student: Computer Science and Technology, [Southeast University](https://www.seu.edu.cn), Nanjing, China

# 💻 Internships
- *2024.11 - 2025.02*: [Hikvision Research](https://www.hikvision.com/cn/) Institute, Hangzhou Hikvision, Hangzhou, China
- *2023.06 - 2025.06*: Healthcare Big Data Lab, [Shenzhen Research Institute of Big Data](https://www.sribd.cn), Shenzhen, China
- *2023.06 - 2025.06*: Advanced Networking and Big Data Lab, [Hangzhou Dianzi University](https://www.hdu.edu.cn), Hangzhou, China


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 We won the **Provincial Silver Medal** in the [China International College Students’ Innovation Competition 2025](https://cy.ncss.cn/)!
- *2025.09*: &nbsp;🎉🎉 Our new paper for [Physics in Medicine & Biology 2025](https://iopscience.iop.org/journal/0031-9155) was **Accpted**!
- *2025.07*: &nbsp;🎉🎉 Our new paper for [IEEE J-BHI 2025](https://www.embs.org/jbhi/) was **Accpted**!
- *2025.06*: &nbsp;🎉🎉 Our new paper for [MICCAI 2025](https://conferences.miccai.org/2025/en/default.asp) was **Accpted**!
- *2025.06*: &nbsp;🎉🎉 We won the **National Third Prize** in the [10th National College Student Life Sciences Competition](https://culsc.cn/)!
- *2024.12*: &nbsp;🎉🎉 We won the **International Bronze Medal** in the [China International College Students' Innovation Competition 2024](https://cy.ncss.cn)!
- *2024.09*: &nbsp;🎉🎉 I am admitted to the Master’s Program in Computer Technology at the School of Computer Science and Engineering, **Southeast University via postgraduate recommendation**!
- *2024.05*: &nbsp;🎉🎉 We won the **Provincial Silver Medal** in the 14th Zhejiang Province ‘Challenge Cup’ College Students’ Entrepreneurship Plan Competition!
- *2024.05*: &nbsp;🎉🎉 We won the **National Bronze Medal** in the [China University Student Service Outsourcing Innovation and Entrepreneurship Competition 2024](http://www.fwwb.org.cn)!
- *2024.04*: &nbsp;🎉🎉 Our new paper for [IEEE J-BHI](https://www.embs.org/jbhi/) was **Accepted**!
- *2024.04*: &nbsp;🎉🎉 Our new paper for [IEEE ISBI 2024](https://biomedicalimaging.org/2024) was selected for **Oral Presentation**!
- *2024.02*: &nbsp;🎉🎉 Our new paper for [IEEE ISBI 2024](https://biomedicalimaging.org/2024) was **Accepted**!
- *2023.12*: &nbsp;🎉🎉 We won the **International Bronze Medal** in the [China International College Students' Innovation Competition 2023](https://cy.ncss.cn)!
- *2023.05*: &nbsp;🎉🎉 Our new paper for [MICCAI 2023](https://conferences.miccai.org/2023/en/) was **Accpted**!
- *2023.06*: &nbsp;🎉🎉 Our new paper for [ICSIP 2023](https://www.icsip.org/2023.html) was **Accepted**!

# 🏅 Honors
- *2021-2025*: The Bachelor of Engineering degree upon graduation from Hangzhou Dianzi University.
- *2021-2025*: The Bachelor of Informatics and Computer Engineering degree With Honors upon graduation from ITMO University (**Top 0.3%**)
- *2024-2025*: Outstanding Graduation Thesis of Hangzhou Dianzi University (**Top 0.2%**)
- *2024-2025*: Zhejiang Provincial Outstanding Graduate (**Top 0.3%**)
- *2023-2024*: National Scholarship (**Top 0.4%**)
- *2023-2024*: [Top 10 Students of HDU-ITMO Joint Institute](https://mp.weixin.qq.com/s/RFjA5qvCV8Tyaz0dk7Jwhg) (**Top 1.25%**)
- *2022-2023*: Zhejiang Provincial Government Scholarship (**Top 3%**)
- *2021-2022*: Zhejiang Provincial Government Scholarship (**Top 3%**)

# 💰 Funding

- *2025*: HDU-ITMO Joint Institute Student Science and Technology Innovation Project (**Key Member**), 💰CNY 3,000.
- *2024*: National Undergraduate Innovation and Entrepreneurship Training Program (**Key Member**), 💰CNY 10,000.
- *2024*: Zhejiang Provincial Undergraduate Scientific and Technological Innovation Activities Program (**Key Member**), 💰CNY 10,000.

# 💡 Publications 
Please visit my [Google Scholar](https://scholar.google.com/citations?user=QEVTqsoAAAAJ&hl=en) page for full publications.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025</div><img src='images/GL-LCM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[GL-LCM: Global-Local Latent Consistency Models for Fast High-Resolution Bone Suppression in Chest X-Ray Images](https://diaoquesang.github.io/GL-LCM-Project-Page/)
  
Yifei Sun, **Zhanghao Chen**, Hao Zheng, Yuqing Lu, Lixin Duan, Fenglei Fan, Ahmed Elazab, Xiang Wan, Changmiao Wang†, Ruiquan Ge†
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE J-BHI 2025</div><img src='images/BS-LDM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[BS-LDM: Effective Bone Suppression in High-Resolution Chest X-Ray Images with Conditional Latent Diffusion Models](https://ieeexplore.ieee.org/document/11079814)
  
Yifei Sun, **Zhanghao Chen**, Hao Zheng, Wenming Deng, Jin Liu, Wenwen Min, Ahmed Elazab, Xiang Wan, Changmiao Wang, Ruiquan Ge†
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ISBI 2024 (Oral)</div><img src='images/BS-Diff.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[BS-Diff: Effective Bone Suppression Using Conditional Diffusion Models from Chest X-Ray Images](https://ieeexplore.ieee.org/abstract/document/10635371/)
  
**Zhanghao Chen**, Yifei Sun, Wenjian Qin, Ruiquan Ge†, Cheng Pan, Wenming Deng, Zhou Liu, Wenwen Min, Ahmed Elazab, Xiang Wan, Changmiao Wang†
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE J-BHI 2024</div><img src='images/UWAFA-GAN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[UWAFA-GAN: ultra-wide-angle fluorescein angiography transformation via multi-scale generation and registration enhancement](https://ieeexplore.ieee.org/abstract/document/10509705/)
  
Ruiquan Ge, Zhaojie Fang, Pengxue Wei, **Zhanghao Chen**, Hongyang Jiang, Ahmed Elazab, Wangting Li, Xiang Wan, Shaochong Zhang, Changmiao Wang†
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2023</div><img src='images/UWAT-GAN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Uwat-gan: Fundus fluorescein angiography synthesis via ultra-wide-angle transformation multi-scale gan](https://link.springer.com/chapter/10.1007/978-3-031-43990-2_70)
  
Zhaojie Fang, **Zhanghao Chen**, Pengxue Wei, Wangting Li, Shaochong Zhang, Ahmed Elazab, Gangyong Jia, Ruiquan Ge†, Changmiao Wang†
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSIP 2023</div><img src='images/RTUNet++.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[RTUNet++: Assessment of Osteosarcoma MRI Image Segmentation leveraging Hybrid CNN-Transformer Approach with Dense Skip Connection](https://ieeexplore.ieee.org/abstract/document/10270849)
  
Binfeng Zou, Yifei Chen, **Zhanghao Chen**, Yifei Sun, Yifan Huang, Feiwei Qin†, Changmiao Wang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Physics in Medicine and Biology 2025</div><img src='images/ICE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Inter-slice Complementarity Enhanced Ring Artifact Removal using Central Region Reinforced Neural Network](N/A)
  
Yikun Zhang, Guannan Liu, **Zhanghao Chen**, Zhiqiang Li, Yuchen Lu, Shengqi Kan, Xinyu Liu, Shipeng Xie, Shouhua Luo, Xu Ji, Yan Xi, Shouping Zhu, Jian Yang, Yang Chen
</div>
</div>


# 🧑🏻‍💻 Software
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024.11</div><img src='images/DMBBSSCXR.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Diffusion Model-Based Bone Suppression System for Chest X-Ray]()
  
Yifei Sun, Ruihan Yang, **Zhanghao Chen**
</div>
</div>

# 🔬 Patent
一种基于条件扩散模型的胸部X光图像骨抑制方法（发明公布）

基于多尺度条件生成对抗网络荧光血管造影图像生成方法（发明公布）

一种基于GL-LCM模型的高分辨率胸部X光图像骨抑制方法（发明公布）

一种基于BS-LDM模型的高分辨率胸部X光图像骨抑制方法（发明公布）

基于不完整三模态共注意融合的轻度认知障碍转换预测方法（发明公布）


# 🤝 Collaborator
[Yifei Sun in Hangzhou Dianzi University](https://diaoquesang.github.io)

[Yifei Chen in Tsinghua University](https://justlfc03.github.io)

[Yikun Zhang in Southeast University](https://cs.seu.edu.cn/yikun/main.htm)

[Zhaojie Fang in The Chinese University of Hong Kong, Shenzhen](https://github.com/Tinysqua)

[Ruiquan Ge in Hangzhou Dianzi University](https://greyspring.github.io)

[Changmiao Wang in Shenzhen Research Institute of Big Data](https://scholar.google.com/citations?user=47KhMXEAAAAJ&hl=en)

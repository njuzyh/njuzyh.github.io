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
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gsfiles_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<br>


# 👋 About me
I am Yuhang Zhou (周 宇航), a fourth-year Ph.D. candidate in Computer Science at the State Key Laboratory for Novel Software Technology, Nanjing University. I am currently under the supervision of [Prof. Chen Tian](https://cs.nju.edu.cn/tianchen/index.htm) and [Dr. Zhibin Wang](https://wzbxpy.github.io/). I am expected to graduate in June 2027. 
<!-- This is my [Chinese CV](../files/yuhang_CV_cn.pdf). -->

# 🌱 Research Interests
- **Machine Learning Systems (MLSys)**
  - *Model training/inference performance optimization* <span style="color: #888;">(ATC '25, ASPLOS '25)</span>
  - *Fault-tolerance in distributed training* <span style="color: #888;">(Arxiv '25)</span>
  - *Large Language Model (LLM) serving scheduling* <span style="color: #888;">(Arxiv '25, Arxiv '24)</span>

- **Distributed Systems & Data Center Networks**
  - *Network performance optimization* <span style="color: #888;">(TPDS '22)</span>
  - *Data-parallel job scheduling* <span style="color: #888;">(TPDS '22)</span>


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 Paper: Hermes is accepted by ATC 2025.
- *2025.01*: &nbsp;🎉🎉 Paper: My paper of roofline analysis is accepted by ASPLOS 2025.
- *2024.08*: &nbsp;🎉🎉 Paper: Sans is accepted by HPEC 2024.
- *2023.06*: &nbsp;🎉🎉 Paper: AFNFA is accepted by APNet 2023.
- *2022.04*: &nbsp;🎉🎉 Paper: Pushbox is accepted by IEEE TPDS.
- *2022.02*: &nbsp;🎉🎉 Paper: Meet is accepted by IEEE TPDS.


# 📝 Publications
<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  ATC'25 &nbsp;</span>
  *Accelerating Model Training on Ascend Chips: An Industrial System for Profiling, Analysis and Optimization*. **(CCF-A)** 📄 [**Paper**](files/paper/atc25-zhou.pdf)
  - 👤 **Yuhang Zhou**, Zibo Wang, Zhibin Wang, Ruyi Zhang, Chen Tian, Xiaoliang Wang, Wanchun Dou, Guihai Chen, Binqiang Wang, Yonghong Tian, Yan Zhang, Hui Wang, Fuchun Wei, Boquan Sun, Jingyi Zhang, Bin She, Teng Su, Yifan Yao, Chunsheng Li, Ziyang Zhang, Yaoyuan Wang, Bin Zhou, Guyue Liu
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  ASPLOS'25 &nbsp;</span>
  *Squeezing Operator Performance Potential for the Ascend Architecture*. **(CCF-A)** 📄 [**Paper**](files/paper/ASPLOS25_Roofline.pdf)
  - 👤 **Yuhang Zhou**, Zhibin Wang, Guyue Liu, Shipeng Li, Xi Lin, Zibo Wang, Yongzhong Wang, Fuchun Wei, Jingyi Zhang, Zhiheng Hu, Yanlin Liu, Chunsheng Li, Ziyang Zhang, Yaoyuan Wang, Bin Zhou, Wanchun Dou, Guihai Chen, Chen Tian
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  HPEC'24 &nbsp;</span>
  *Sans: Streaming Anonymized Network Sensing*. 📄 [**Paper**](files/paper/HPEC24_Sans.pdf)
  - 👤 Ketai Zhao, **Yuhang Zhou**, Hongxu Pan, Zhibin Wang, Sheng Zhong and Chen Tian
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  APNet'23 Poster &nbsp;</span>
  *AFNFA: An Approach to Automate NCCL Configuration Exploration*. 📄 [**Paper**](files/paper/APNet23_AFNFA.pdf)
  - 👤 Zibo Wang, **Yuhang Zhou**, Chen Tian, Xiaoliang Wang, Xianping Chen
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  IEEE TPDS &nbsp;</span>
  *PushBox: Making Use of Every Bit of Time to Accelerate Completion of Data-parallel Jobs*. **(CCF-A)** 📄 [**Paper**](files/paper/TPDS22_Pushbox.pdf)
  - 👤 Chen Tian, Yi Wang, Bingchuan Tian, Yang Zhao, **Yuhang Zhou**, Chenxu Wang, Haoran Guan, Wanchun Dou, and Guihai Chen
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  IEEE TPDS &nbsp;</span>
  *MEET: rack-level pooling based load balancing in datacenter networks*. **(CCF-A)** 📄 [**Paper**](files/paper/TPDS22_Meet.pdf)
  - 👤 Jiaqing Dong, Lijuan Tan, Chen Tian, **Yuhang Zhou**, Yi Wang, Wanchun Dou, and Guihai Chen
</div>


# 📰 Preprints
<div class='paper-box-text' markdown="1">
- <span style="background-color: orange; color: white; font-size: 0.85em;">&nbsp;
  Arxiv 25 &nbsp;</span>
  *ElasWave: An Elastic-Native System for Scalable Hybrid-Parallel Training*. 📄 [**Paper**](https://arxiv.org/abs/2510.00606)
  - 👤 Xueze Kang, Guangyu Xiang, Yuxin Wang, Hao Zhang, Yuchu Fang, **Yuhang Zhou**, Zhenheng Tang, Youhui Lv, Eliran Maman, Mark Wasserman, Alon Zameret, Zhipeng Bian, Shushu Chen, Zhiyou Yu, Jin Wang, Xiaoyu Wu, Yang Zheng, Chen Tian, Xiaowen Chu
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: orange; color: white; font-size: 0.85em;">&nbsp;
  Arxiv 25 &nbsp;</span>
  *Chameleon: Taming Dynamic Operator Sequences for Memory-Intensive LLM Training*. 📄 [**Paper**](https://arxiv.org/abs/2509.11076)
  - 👤 Zibo Wang, **Yuhang Zhou**, Zhibin Wang, Shipeng Li, Xinjing Huang, Chendong Cai, Bingxu Mu, Yuqing Sun, Zhiheng Hu, Bin She, Shu You, Guanghuan Fang, Rong Gu, Wanchun Dou, Guihai Chen, Chen Tian
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: orange; color: white; font-size: 0.85em;">&nbsp;
  Arxiv 25 &nbsp;</span>
  *Accelerating Mixture-of-Experts Inference by Hiding Offloading Latency with Speculative Decoding*. 📄 [**Paper**](https://arxiv.org/abs/2508.21706)
  - 👤 Zhibin Wang, Zhonghui Zhang, **Yuhang Zhou**, Zibo Wang, Mo Zhou, Peng Jiang, Weilin Cai, Chengying Huan, Rong Gu, Sheng Zhong, Chen Tian
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: orange; color: white; font-size: 0.85em;">&nbsp;
  Arxiv 25 &nbsp;</span>
  *Odyssey: Adaptive Policy Selection for Resilient Distributed Training*. 📄 [**Paper**](https://arxiv.org/abs/2508.21613)
  - 👤 **Yuhang Zhou**, Zhibin Wang, Peng Jiang, Haoran Xia, Junhe Lu, Qianyu Jiang, Rong Gu, Hengxi Xu, Xinjing Huang, Guanghuan Fang, Zhiheng Hu, Jingyi Zhang, Yongjin Cai, Jian He, Chen Tian
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: orange; color: white; font-size: 0.85em;">&nbsp;
  Arxiv 25 &nbsp;</span>
  *Echo: Efficient Co-Scheduling of Hybrid Online-Offline Tasks for Large Language Model Serving*. 📄 [**Paper**](https://arxiv.org/abs/2504.03651)
  - 👤 Zhibin Wang, Shipeng Li, Xue Li, **Yuhang Zhou**, Zhonghui Zhang, Zibo Wang, Rong Gu, Chen Tian, Kun Yang, Sheng Zhong
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: orange; color: white; font-size: 0.85em;">&nbsp;
  Arxiv 24 &nbsp;</span>
  *Revisiting SLO and Goodput Metrics in LLM Serving*. 📄 [**Paper**](https://arxiv.org/abs/2410.14257)
  - 👤 Zhibin Wang, Shipeng Li, **Yuhang Zhou**, Xue Li, Rong Gu, Nguyen Cam-Tu, Chen Tian, Sheng Zhong
</div>


# 🏆 Honors and Awards
- *2025.10*: Awarded National Scholarship for Ph.D. students.
- *2025.04*: Postgraduate Research & Practice Innovation Program of Jiangsu Province.
- *2024.08*: IEEE HPEC Graph Challenge 2024 Honorable Mention.

# 🎓 Educations
- *2021.09 - (now)*, Nanjing University, China. Ph.D in Computer Science and Technology, supervised by [Prof. Chen Tian](https://cs.nju.edu.cn/tianchen/index.htm).
- *2016.09 - 2020.06*, Nanjing University, China. B.S in Computer Science and Technology.

# 💻 Internships
- *2023.01 - (now)*, Huawei, China, supervised by Jingyi Zhang.
- *2022.07 - 2022.12*, Pengcheng Lab, China, supervised by Bingqiang Wang.

# 📚 Teaching
- *2025.09 - *, Teaching Assistant, LLM System and Engineering, Fall 2025, Nanjing University.
- *2025.03 - 2025.06*, Teaching Assistant, Deep Learning Platform and Application, Spring 2025, Nanjing University.
- *2022.02 - 2022.06*, Teaching Assistant, Computer Network, Spring 2022, Nanjing University.

<!-- <div style="width: 250px; height: 250px; margin: auto; border: 1px solid #ddd; border-radius: 10px;">
  <script type="text/javascript" id="clstr_globe" src="https://clustrmaps.com/globe.js?d=qW1Hdbab0yqtSVhvkgvntv3GDKfftXspfZhTGV-XIWM"></script>
</div> -->

# 🌍 Visitors
<div style="width: 250px; margin: auto; border: 1px solid #ddd; border-radius: 10px;">
  <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=qW1Hdbab0yqtSVhvkgvntv3GDKfftXspfZhTGV-XIWM&cl=ffffff&w=a"></script>
</div>
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

I am a Ph.D. student at [Department of Electronic Engineering](https://www.ee.cuhk.edu.hk/en-gb/), [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html), advised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang). I collaborate closely with [Long Bai](https://longbai-cuhk.github.io/) at our [MEDICAL MECHATRONICS Lab](http://www.labren.org/mm/lab/). Previously, I received the M. Sc. degree in Department of Electronic Engineering from The Chinese University of Hong Kong in 2023, advised by Prof. Hongliang Ren. I also received my Bachelor degree in Automation at [College of Mechatronics and Control Engineering](https://cmce.szu.edu.cn/), [Shenzhen University](https://www.szu.edu.cn/), advised by [Prof. Xiaopin Zhong](https://cmce.szu.edu.cn/info/1686/5238.htm).

My research interests include computer vision and its applications in medical image analysis and surgical robotic perception. I recently work on large vision-language models and downstream surgical robot control.

<!-- <img src="images/my.jpg" alt="sym" width="50%" style="display: block; margin: 0 auto;"> -->


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper GRAD is accepted by [**Information Fusion**](https://www.sciencedirect.com/journal/information-fusion) (IF: 14.8).
- *2025.02*: &nbsp;🎉🎉 Our work "PDZSeg: Adapting the Foundation Model for Dissection Zone Segmentation with Visual Prompts in Robot-assisted Endoscopic Submucosal Dissection" is accepted by [**IPCAI 2025**](https://sites.google.com/view/ipcai2025)!
- *2025.01*: &nbsp;🎉🎉 Our work "ETSM: Automating Dissection Trajectory Suggestion and Confidence Map-Based Safety Margin Prediction for Robot-assisted Endoscopic Submucosal Dissection" is accepted by [**ICRA 2025**](https://2025.ieee-icra.org/)!
- *2025.01*: &nbsp;🎉🎉 One paper TSUBF-Net is published by [**Neural Computing and Applications**](https://link.springer.com/article/10.1007/s00521-024-10824-9) (IF: 4.8).
- *2024.08*: &nbsp;🎉🎉 One paper Surgical-VQLA++ is published by [**Information Fusion**](https://www.sciencedirect.com/science/article/pii/S1566253524003804) (IF: 14.8).


<span class='anchor' id='publications'></span>
# 📝 Selected Publications [Find full list at Google Scholar]

† indicates equal contribution; * represents the corresponding authors.
- **Surgical-VQLA++: Adversarial contrastive learning for calibrated robust visual question-localized answering in robotic surgery**<br>
  Long Bai†, **Guankun Wang†**, Mobarakol Islam†, Lalithkumar Seenivasan, An Wang, Hongliang Ren*<br>
  Information Fusion (IF), 2024. (IF: 14.8)

- **Multimodal Graph Representation Learning for Robust Surgical Workflow Recognition with Adversarial Feature Disentanglement**<br>
  Long Bai†, Boyi Ma†, Ruohan Wang, **Guankun Wang**, Beilei Cui, Zhongliang Jiang, Mobarakol Islam, Zhe Min, 	Jiewen Lai, Nassir Navab, Hongliang Ren*<br>
  Information Fusion (IF), 2025. (IF: 14.8)

- **ETSM: Automating Dissection Trajectory Suggestion and Confidence Map-Based Safety Margin Prediction for Robot-assisted Endoscopic Submucosal Dissection**<br>
  Mengya Xu†, Wenjin Mo†, **Guankun Wang†**, Huxin Gao, An Wang, Long Bai, Chaoyang Lyu, Xiaoxiao Yang, Zhen Li, Hongliang Ren*<br>
  IEEE International Conference on Robotics and Automation (ICRA 2025). (CCF-B)

- **PDZSeg: Adapting the Foundation Model for Dissection Zone Segmentation with Visual Prompts in Robot-assisted Endoscopic Submucosal Dissection**<br>
  Mengya Xu, Wenjin Mo, **Guankun Wang**, Huxin Gao, An Wang, Zhen Li, Xiaoxiao Yang, Hongliang Ren*<br>
  International Conference on Information Processing in Computer-Assisted Interventions (IPCAI 2025).

- **TSUBF-Net: Trans-spatial UNet-like network with Bi-direction fusion for segmentation of adenoid hypertrophy in CT**<br>
  Rulin Zhou, Yingjie Feng, **Guankun Wang**, Xiaopin Zhong, Zongze Wu, Qiang Wu* & Xi Zhang <br>
  Neural Computing and Applications (NCAP), 2025. (IF: 4.8)

- **Towards Open-Set Surgical Activity Recognition in Robot-assisted Surgery**<br>
  Long Bai†, **Guankun Wang†**, Jie Wang, Xiaoxiao Yang, Huxin Gao, Xin Liang, An Wang, Mobarakol Islam, 	Hongliang Ren*<br>
  IEEE International Conference on Robotics and Automation (ICRA 2024). (CCF-B)

- **Uncertainty-aware Out-of-distribution Detection in Capsule Endoscopy Diagnosis**<br>
  Qiaozhi Tan†, Long Bai†, **Guankun Wang†**, Mobarakol Islam, Hongliang Ren*<br>
  IEEE International Symposium on Biomedical Imaging (ISBI 2024).

- **Rethinking Exemplars for Continual Semantic Segmentation in Endoscopy Scenes: Entropy-based Mini-Batch Pseudo-Replay**<br>
  **Guankun Wang†**, Long Bai†, Yanan Wu, Tong Chen, Hongliang Ren*<br>
  Computers in Biology and Medicine (CBM), 2023.

- **Domain Adaptive Sim-to-Real Segmentation of Oropharyngeal Organs**<br>
  **Guankun Wang**, Tian-Ao Ren, Jiewen Lai, Long Bai, and Hongliang Ren<br>
  Medical & Biological Engineering & Computing (MBEC), 2023.

- **Mask Focal Loss: A unifying framework for dense crowd counting with canonical object detection networks**<br>
  Xiaopin Zhong, **Guankun Wang**, Weixiang Liu*, Zongze Wu, Yuanlong Deng<br>
  Multimedia Tools and Applications (MTAP), Accepted, 2023.

- **An Improved FairMOT Method for Crowd Tracking and Counting in Subway Passages**<br>
  **Guankun Wang**, Yongze Yang, Xiaopin Zhong*, Yang Yang<br>
  IEEE International Conference on Intelligent Transportation Engineering (ICITE 2021).<br>
  **Best Student Paper Award**

<span class='anchor' id='awards'></span>
# 🎖 Selected Awards
- *2024.05* **Best Poster Award of ICRA 2024 C4SR+ Workshop**
- *2023.11* **HAMEN FAN SCHOLARSHIP for M.Sc.in ELECTRONIC ENGINEERING**
- *2023.11* **Dean's List 2022-2023**
- *2023.07* **Best Poster Award at ICRA 2023 Workshop**
- *2022.10* **Department Admission Scholarship**
- *2022.07* **Outstanding Graduate Student**

<span class='anchor' id='work'></span>
# 📖 Educations
- *2024.08 - 2028.07*, Ph.D., Electronic Engineering, The Chinese University of Hong Kong, Hong Kong SAR, China
- *2022.09 - 2023.07*, M.Sc., Electronic Engineering, The Chinese University of Hong Kong, Hong Kong SAR, China
- *2018.09 - 2022.07*, B.Eng., Automation, Shenzhen University, Shenzhen, China

<span class='anchor' id='work'></span>
# 💻 Work Experience
- *2023.09 - 2024.07*, [Junior Research Assistant] Department of Electronic Engineering, The Chinese University of Hong Kong, Hong Kong. Supervised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang).
- *2021.07 - 2021.12*, [Application Engineer Intern] Research and Development Department, DAS Intelligence, Shenzhen, China.

<span class='anchor' id='work'></span>
# 💬 Professional Services
- Regular Journal and Conference Reviewer:
  IJCARS, International Journal of Machine Learning and Cybernetics, Image and Vision Computing, MICCAI, ISBI, IPCAI

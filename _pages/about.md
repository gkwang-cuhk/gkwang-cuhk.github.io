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

I am a Ph.D. student at [Department of Electronic Engineering](https://www.ee.cuhk.edu.hk/en-gb/), [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html), advised by [Prof. Hongliang Ren](https://www.ee.cuhk.edu.hk/en-gb/people/academic-staff/professors/prof-ren-hongliang). I collaborate closely with [Dr. Long Bai](https://longbai-cuhk.github.io/) at our Alibaba DAMO Academy, [Prof. Huxin Gao](https://ghx-0228.github.io/) at our [MEDICAL MECHATRONICS Lab](http://www.labren.org/mm/lab/) and [Prof. Jinlin Wu](https://scholar.google.com/citations?user=XujjZmUAAAAJ&hl=en) at [Hong Kong Institute of Science & Innovation, Chinese Academy of Sciences](https://www.cair-cas.org.hk/). Previously, I received the M. Sc. degree in Department of Electronic Engineering from The Chinese University of Hong Kong in 2023, advised by Prof. Hongliang Ren. I also received my Bachelor degree in Automation at [College of Mechatronics and Control Engineering](https://cmce.szu.edu.cn/), [Shenzhen University](https://www.szu.edu.cn/), advised by [Prof. Xiaopin Zhong](https://cmce.szu.edu.cn/info/1686/5238.htm).

My research interests include computer vision and its applications in medical image analysis and surgical robotic perception. I recently work on large vision-language models and downstream surgical robot control.

<!-- <img src="images/my.jpg" alt="sym" width="50%" style="display: block; margin: 0 auto;"> -->


# 🔥 News
- *2025.08*: &nbsp;🎉🎉 One paper [**EndoChat**](https://arxiv.org/pdf/2501.11347) is accepted by [**Medical Image Analysis**](https://www.sciencedirect.com/journal/medical-image-analysis) (IF: 11.8).
- *2025.08*: &nbsp;🎉🎉 One paper [**CoPESD**](https://arxiv.org/pdf/2410.07540?) is accepted by [**ACM Multimedia 2025**](https://acmmm2025.org/).
- *2025.08*: &nbsp;🎉🎉 One paper [**EndoVLA**](https://arxiv.org/pdf/2505.15206) is accepted by [**CoRL 2025**](https://www.corl.org/).
- *2025.07*: &nbsp;🎉🎉 One paper [**SurgCSS**](https://discovery.ucl.ac.uk/id/eprint/10212110/1/Hoque_Rethinking%20data%20imbalance%20in%20class%20incremental%20surgical%20instrument%20segmentation.pdf) is accepted by [**Medical Image Analysis**](https://www.sciencedirect.com/journal/medical-image-analysis) (IF: 11.8).
- *2025.07*: &nbsp;🎉🎉 One paper [**Geo-RepNet**](https://arxiv.org/abs/2507.09294) is accepted by [**ICIA 2025**](https://www.icia2025.org/index.html).
- *2025.06*: &nbsp;🎉🎉 One paper [**SurgTPGS**](https://arxiv.org/abs/2506.23309) is accepted by [**MICCAI 2025**](https://conferences.miccai.org/2025/en/).
- *2025.06*: &nbsp;🎉🎉 One paper [**EndoARSS**](https://www.arxiv.org/abs/2506.06830) is accepted by [**Advanced Intelligent Systems**](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/aisy.202500288) (IF: 6.1).
- *2025.06*: &nbsp;🎉🎉 Our work "PDZSeg: Adapting the Foundation Model for Dissection Zone Segmentation with Visual Prompts in Robot-assisted Endoscopic Submucosal Dissection" is published by [**International Journal of Computer Assisted Radiology and Surgery**](https://link.springer.com/article/10.1007/s11548-025-03437-7)!
- *2025.05*: &nbsp;🎉🎉 One paper GRAD is accepted by [**Information Fusion**](https://www.sciencedirect.com/journal/information-fusion) (IF: 15.5).
- *2025.01*: &nbsp;🎉🎉 Our work "ETSM: Automating Dissection Trajectory Suggestion and Confidence Map-Based Safety Margin Prediction for Robot-assisted Endoscopic Submucosal Dissection" is accepted by [**ICRA 2025**](https://2025.ieee-icra.org/)!




<span class='anchor' id='publications'></span>
# 📝 Selected Publications [Find full list at Google Scholar]
† indicates equal contribution; * represents the corresponding authors.
- **EndoChat: Grounded Multimodal Large Language Model for Endoscopic Surgery**<br>
  **Guankun Wang**†, Long Bai†, Junyi Wang†, Kun Yuan†, Zhen Li, Tianxu Jiang, Xiting He, Jinlin Wu, Zhen Chen, Zhen Lei, Hongbin Liu, Jiazheng Wang, Fan Zhang, Nicolas Padoy, Nassir Navab, Hongliang Ren*<br>
  Medical Image Analysis (MedIA), 2025.

- **Rethinking data imbalance in class incremental surgical instrument segmentation**<br>
  Shifang Zhao, Long Bai, Kun Yuan, Feng Li, Jieming Yu, Wenzhen Dong, **Guankun Wang**, Mobarak Islam Hoque, Nicolas Padoy, Nassir Navab, Hongliang Ren*<br>
  Medical Image Analysis (MedIA), 2025.

- **CoPESD: A Multi-Level Surgical Motion Dataset for Training Large Vision-Language Models to Co-Pilot Endoscopic Submucosal Dissection**<br>
  **Guankun Wang**†, Han Xiao†, Huxin Gao, Renrui Zhang, Long Bai, Xiaoxiao Yang, Zhen Li, Hongsheng Li*, Hongliang Ren*<br>
  Proceedings of the 33rd ACM International Conference on Multimedia (ACM Multimedia 2025)

- **EndoVLA: Dual-Phase Vision-Language-Action Model for Autonomous Tracking in Endoscopy**<br>
  Chi Kit Ng†, Long Bai†, **Guankun Wang**†, Yupeng Wang, Huxin Gao, Kun Yuan, Chenhan Jin, Tieyong Zeng, Hongliang Ren*<br>
  The Conference on Robot Learning (CoRL) 2025

- **SurgTPGS: Semantic 3D Surgical Scene Understanding with Text Promptable Gaussian Splatting**<br>
  Yiming Huang†, Long Bai†, Beilei Cui†, Kun Yuan, **Guankun Wang**, Mobarakol Islam, Nicolas Padoy, Nassir Navab, Hongliang Ren*<br>
  International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2025)

- **Multimodal Graph Representation Learning for Robust Surgical Workflow Recognition with Adversarial Feature Disentanglement**<br>
  Long Bai†, Boyi Ma†, Ruohan Wang, **Guankun Wang**, Beilei Cui, Zhongliang Jiang, Mobarakol Islam, Zhe Min, 	Jiewen Lai, Nassir Navab, Hongliang Ren*<br>
  Information Fusion (IF), 2025. 

- **EndoARSS: Adapting Spatially-Aware Foundation Model for Efficient Activity Recognition and Semantic Segmentation in Endoscopic Surgery**<br>
  **Guankun Wang†**, Rui Tang†, Mengya Xu†, Long Bai, Huxin Gao, Hongliang Ren*<br>
   Advanced Intelligent Systems (AIS), 2025. 

- **STAR: Empowering Semi-Supervised Medical Image Segmentation with SAM-based Teacher-Student Architecture and Contrastive Consistency Regularization**<br>
  Qiwei Liang, Rulin Zhou, Yijing Zhou, **Guankun Wang**, Peng Peng, Xiaopin Zhong*<br>
   Expert Systems with Applications (ESAP), 2025. 
  
- **Surgical-VQLA++: Adversarial contrastive learning for calibrated robust visual question-localized answering in robotic surgery**<br>
  Long Bai†, **Guankun Wang†**, Mobarakol Islam†, Lalithkumar Seenivasan, An Wang, Hongliang Ren*<br>
  Information Fusion (IF), 2024. 

- **ETSM: Automating Dissection Trajectory Suggestion and Confidence Map-Based Safety Margin Prediction for Robot-assisted Endoscopic Submucosal Dissection**<br>
  Mengya Xu†, Wenjin Mo†, **Guankun Wang†**, Huxin Gao, An Wang, Long Bai, Chaoyang Lyu, Xiaoxiao Yang, Zhen Li, Hongliang Ren*<br>
  IEEE International Conference on Robotics and Automation (ICRA 2025). (CCF-B)

- **PDZSeg: Adapting the Foundation Model for Dissection Zone Segmentation with Visual Prompts in Robot-assisted Endoscopic Submucosal Dissection**<br>
  Mengya Xu, Wenjin Mo, **Guankun Wang**, Huxin Gao, An Wang, Zhen Li, Xiaoxiao Yang, Hongliang Ren*<br>
  International Conference on Information Processing in Computer-Assisted Interventions (IPCAI 2025).

- **TSUBF-Net: Trans-spatial UNet-like network with Bi-direction fusion for segmentation of adenoid hypertrophy in CT**<br>
  Rulin Zhou, Yingjie Feng, **Guankun Wang**, Xiaopin Zhong, Zongze Wu, Qiang Wu* & Xi Zhang <br>
  Neural Computing and Applications (NCAP), 2025. 

- **Towards Open-Set Surgical Activity Recognition in Robot-assisted Surgery**<br>
  Long Bai†, **Guankun Wang†**, Jie Wang, Xiaoxiao Yang, Huxin Gao, Xin Liang, An Wang, Mobarakol Islam, 	Hongliang Ren*<br>
  IEEE International Conference on Robotics and Automation (ICRA 2024). (CCF-B)

- **Uncertainty-aware Out-of-distribution Detection in Capsule Endoscopy Diagnosis**<br>
  Qiaozhi Tan†, Long Bai†, **Guankun Wang†**, Mobarakol Islam, Hongliang Ren*<br>
  IEEE International Symposium on Biomedical Imaging (ISBI 2024).

- **Rethinking Exemplars for Continual Semantic Segmentation in Endoscopy Scenes: Entropy-based Mini-Batch Pseudo-Replay**<br>
  **Guankun Wang†**, Long Bai†, Yanan Wu, Tong Chen, Hongliang Ren*<br>
  Computers in Biology and Medicine (CBM), 2023.  


<span class='anchor' id='awards'></span>
# 🎖 Selected Awards
- *2025.10* **First Place Award at ACM MM 2025 Workshop**
- *2025.10* **Best Poster Award at IROS 2025 Workshop**
- *2025.10* **MICCAI Young Scientist Award (5/3677)**
- *2025.06* **The IHU Strasbourg and NDI Bench to Bedside Award: Honorable Mention**
- *2025.05* **MRC Symposium Best Application Award**
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
  Information Fusion, Scientific Reports, IJCARS, International Journal of Machine Learning and Cybernetics, Image and Vision Computing, ICRA, MICCAI, ISBI, IPCAI
- Conference Session Chair:
  ACM MM 2025, ICBIR 2025, ICIA 2025

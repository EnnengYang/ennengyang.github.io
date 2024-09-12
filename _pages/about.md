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

👋 Hello! This is Enneng Yang. 
I'm currently a fourth-year Ph.D. student in Software College, [Northeastern University, China](https://www.neu.edu.cn/), advised by [Prof. Guibing Guo](https://guoguibing.github.io/cn/). I had the privilege of working closely with [Assoc. Prof. Li Shen](https://sites.google.com/site/mathshenli/home) and [Dr. Zhenyi Wang](https://sites.google.com/view/zhenyiwang). From March 2024 to March 2025, I am a visiting Ph.D. student in [Prof. Jie Zhang](https://personal.ntu.edu.sg/zhangj/)'s group at [Nanyang Technological University, Singapore](https://www.ntu.edu.sg/).


My research interests lie in machine learning and  recommender system. More specifically, I focus on:
- **Machine Learning:** foundation models, model merging, multi-task learning, continual/incremental learning, data-free learning, dataset/knowledge distillation
- **Recommendation System:** multi-task/multi-scenario recommendation, sequential recommendation, robust recommendation, CTR/CVR prediction, discrete recommendation


# 🔥 News

- 2024.09: 🎉 Our paper about continual learning is accepted to TPAMI 2024.
- 2024.07: 🎉 Our paper about sequential recommendation is accepted to RecSys 2024.
- 2024.06: 🎉 Our paper about deconfounding recommendation is accepted to ACM TKDD 2024.
- 2024.05: 🎉 Our paper about model merging is accepted to ICML 2024.
- 2024.02: 🎉 Our paper about multi-task recommendation is accepted to ACM TKDD 2024.
- 2024.01: 🎉 Our paper about model merging is accepted to ICLR 2024.
- 2023.10: 🎉 Our paper about explanation recommendation is accepted to KBS 2023.
- 2023.10: 🎉 Our paper about sequential recommendation is accepted to TKDE 2023.
- 2023.09: 🎉 Our paper about dataset condensation is accepted to NeurIPS 2023.
- 2023.07: 🎉 Our paper about flatness-aware continual learning is accepted to ICCV 2023.
- 2023.04: 🎉 Our paper about next-baseket recommendation is accepted to IJCAI 2023.

<!-- 
&nbsp;🎉 
&nbsp;🎓 
&nbsp;🏅
-->

# ✨ Repositories

😄 Comments and contributions are welcome.

- [**Awesome-Model-Merging-Methods-Theories-Applications**](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) [![](https://img.shields.io/github/stars/ennengyang/Awesome-Model-Merging-Methods-Theories-Applications?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) \
  This repository collects the latest research progress of Moedel Merging in Machine Learning. 
- [**Awesome-Forgetting-in-Deep-Learning**](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) [![](https://img.shields.io/github/stars/ennengyang/Awesome-Forgetting-in-Deep-Learning?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) \
  This repository collects the latest research progress of Catastrophic Forgetting in Deep Learning.

<!-- 
# 📝 Selected Preprints 

- Model Merging in LLMs, MLLMs, and Beyond: Methods, Theories, Applications and Opportunities \
  `Arxiv 2024` <font color="red">Survery Paper</font> | [**Paper**](https://arxiv.org/pdf/2408.07666) [**Code**](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) \
  **Enneng Yang**, Li Shen, Guibing Guo, Xingwei Wang, Xiaochun Cao, Jie Zhang, Dacheng Tao.
  
- A Comprehensive Survey of Forgetting in Deep Learning Beyond Continual Learning \
  `Arxiv 2023` <font color="red">Survery Paper</font>  | [**Paper**](https://arxiv.org/pdf/2307.09218) [**Code**](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) \
  Zhenyi Wang, **Enneng Yang**, Li Shen, Heng Huang.
-->

  
# 📝 Selected Publications 

<!-- -
<a href="https://www.ccf.org.cn/Academic_Evaluation/By_category/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CCF-Rank]</a>
<a href="https://www.caai.cn/index.php?s=/home/article/detail/id/3445.html" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CCAI-Rank]</a>
<a href="http://portal.core.edu.au/conf-ranks/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CORE-Rank (conf)]</a>
<a href="http://portal.core.edu.au/jnl-ranks/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CORE-Rank (jnl)]</a>
-->

[comment]: <> (<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>)
[comment]: <> (<div class='paper-box-text' markdown="1">)
[comment]: <> ([Deep Residual Learning for Image Recognition]&#40;https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf&#41;)
[comment]: <> (**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun)
[comment]: <> ([**Project**]&#40;https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC&#41; <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>)
[comment]: <> (- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )
[comment]: <> (</div>)
[comment]: <> (</div>)

$^{\ast}$ indicates equal contribution, $^{\dagger}$ indicates corresponding author

## Survey Papers

- Model Merging in LLMs, MLLMs, and Beyond: Methods, Theories, Applications and Opportunities \
  `Arxiv 2024` | [**Paper**](https://arxiv.org/pdf/2408.07666) [**Code**](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) \
  **Enneng Yang**, Li Shen, Guibing Guo, Xingwei Wang, Xiaochun Cao, Jie Zhang, Dacheng Tao.
  
- A Comprehensive Survey of Forgetting in Deep Learning Beyond Continual Learning \
  `Arxiv 2023` | [**Paper**](https://arxiv.org/pdf/2307.09218) [**Code**](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) \
  Zhenyi Wang, **Enneng Yang**, Li Shen, Heng Huang.
  
## Conference Papers

- Representation Surgery for Multi-Task Model Merging\
  `ICML 2024` | [**Paper**](https://openreview.net/pdf?id=Sbl2keQEML) [**Code**](https://github.com/EnnengYang/RepresentationSurgery)  \
  **Enneng Yang**, Li Shen, Zhenyi Wang, Guibing Guo, Xiaojun Chen, Xingwei Wang, Dacheng Tao.

- AdaMerging: Adaptive Model Merging for Multi-Task Learning\
  `ICLR 2024` | [**Paper**](https://openreview.net/pdf?id=nZP6NgD3QY) [**Code**](https://github.com/EnnengYang/AdaMerging)  \
  **Enneng Yang**, Zhenyi Wang, Li Shen, Shiwei Liu, Guibing Guo, Xingwei Wang, Dacheng Tao.

- An Efficient Dataset Condensation Plugin and Its Application to Continual Learning\
  `NeurIPS 2023` | [**Paper**](https://openreview.net/pdf?id=Murj6wcjRw) [**Code**](https://github.com/EnnengYang/An-Efficient-Dataset-Condensation-Plugin)  \
  **Enneng Yang**, Li Shen, Zhenyi Wang, Tongliang Liu, Guibing Guo.

- Data Augmented Flatness-aware Gradient Projection for Continual Learning\
  `ICCV 2023` | [**Paper**](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_Data_Augmented_Flatness-aware_Gradient_Projection_for_Continual_Learning_ICCV_2023_paper.pdf)  [**Supplemental**](https://openaccess.thecvf.com/content/ICCV2023/supplemental/Yang_Data_Augmented_Flatness-aware_ICCV_2023_supplemental.pdf) [**Code**](https://github.com/EnnengYang/DFGP)   \
  **Enneng Yang**, Li Shen, Zhenyi Wang, Shiwei Liu, Guibing Guo, Xingwei Wang.

- AdaTask: A Task-aware Adaptive Learning Rate Approach to Multi-task Learning\
  `AAAI 2023` (Oral) | [**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/26275)  [**Supplemental**](https://arxiv.org/pdf/2211.15055)  [**Code**](https://github.com/EnnengYang/AdaTask)  \
  **Enneng Yang**, Junwei Pan, Ximei Wang, Haibin Yu, Li Shen, Xihua Chen, Lei Xiao, Jie Jiang, Guibing Guo.

- Basket Representation Learning by Hypergraph Convolution on Repeated Items for Next-basket Recommendation\
  `IJCAI 2023` (Oral) | [**Paper**](https://www.ijcai.org/proceedings/2023/0268.pdf) \
  Yalin Yu $^{\ast}$, **Enneng Yang** $^{\ast}$,  Guibing Guo, Linying Jiang, Xingwei Wang.

- Uniform Sequence Better: Time Interval Aware Data Augmentation for Sequential Recommendation\
  `AAAI 2023` (Oral) | [**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/25540) [**Code**](https://github.com/KingGugu/TiCoSeRec)\
 Yizhou Dang, **Enneng Yang**, Guibing Guo, Linying Jiang, Xingwei Wang, Xiaoxiao Xu, Qinghui Sun, Hong Liu.

- Discrete Trust-aware Matrix Factorization for Fast Recommendation\
  `IJCAI 2019` (Oral) | [**Paper**](https://www.ijcai.org/proceedings/2019/0191.pdf) [**Code**](https://github.com/EnnengYang/DTMF)\
 Guibing Guo, **Enneng Yang** $^{\dagger}$, Li Shen $^{\dagger}$, Xiaochun Yang, Xiaodong He.

## Journal Papers
- Continual Learning From a Stream of APIs \
  `TPAMI 2024` | (Just accepted) \
  **Enneng Yang**, Zhenyi Wang, Li Shen, Nan Yin, Tongliang Liu, Guibing Guo, Xingwei Wang, Dacheng Tao.
  
- TiCoSeRec: Augmenting Data to Uniform Sequences by Time Intervals for Effective Recommendation\
  `TKDE 2023` | [**Paper**](https://ieeexplore.ieee.org/document/10285049) \
  Yizhou Dang, **Enneng Yang**, Guibing Guo, Linying Jiang, Xingwei Wang, Xiaoxiao Xu, Qinghui Sun, Hong Liu.


# 📖 Educations

- *2024.03 - 2025.03*: Visiting Ph.D. Student in [Nanyang Technological University, Singapore](https://www.ntu.edu.sg/).
- *2021.09 - 2025.07 (Expected)*: Ph.D. Student in [Northeastern University, China](https://www.neu.edu.cn/).

<!--
- *2018.09 - 2021.07*: M.S. Student in [Northeastern University, China](https://www.neu.edu.cn/).
-->


# 💻 Internships

- *2023.05 - 2023.09*: Intern at [Digital China Group Co., Ltd](https://www.digitalchina.com/).
- *2022.01 - 2022.06*: Research Intern at [Tencent Inc](https://www.tencent.com/), mentored by [Junwei Pan](https://scholar.google.com/citations?user=sUaBkFkAAAAJ&hl=zh-TW).
- *2020.05 - 2021.02*: Research Intern at [Tencent Inc](https://www.tencent.com/), mentored by [Junwei Pan](https://scholar.google.com/citations?user=sUaBkFkAAAAJ&hl=zh-TW) and Dr. Xiaoqing Cao. (2020 Tencent Rhino-Bird Elite Talent Training Program)


# 🏆 Honors and Awards

- *2023*: National Scholarship (Top 1%)
- *2019*: National Scholarship (Top 1%)
- *2017*: National Scholarship (Top 1%)


# 🔖 Service

- Conference Reviewers: 
  - International Conference on Learning Representations (ICLR) 2025
  - AAAI Conference on Artificial Intelligence (AAAI) 2025
  - Conference on Neural Information Processing Systems (NeurIPS) 2024
  - International Conference on Machine Learning (ICML) 2024
  - ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD) 2024
  - AAAI Conference on Artificial Intelligence (AAAI) 2024
  - The Web Conference (International World Wide Web Conference) (WWW) 2023
  - ACM International Conference on Web Search and Data Mining (WSDM) 2023
- Journal Reviewers:
  - IIEEE Transactions on Big Data (TBD) 2024
  - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT) 2024
  - Neural Computing and Applications (NCAA) 2024
  - ACM Transactions on Recommender Systems (TORS) 2022

<!--
# 💬 Contact
- Address 1: Northeastern University, No.195, Chuangxin Road, Hunnan District, Shenyang City, Liaoning Province, P.R.China, 110169.
- Address 2: Nanyang Technological University, 50 Nanyang Avenue, Singapore, 639798. (Current Address)
- Email: ennengyang(at)stumail.neu.edu.cn / n2308949l(at)e.ntu.edu.sg
-->

<!--
# 💬 Invited Talks
- *2024.07* 
-->

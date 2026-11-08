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

I'm a PhD candidate under the advisement of [Xiang Li](https://lixiang3776.github.io/) at East China Normal University, DaSE. I'm currently interning at Baidu Inc.

My research interest includes large language models, graph neural networks, deep generative models, molecular learning, and recommender systems. 

Check out my published papers at <a href='https://scholar.google.com/citations?user=6tJ39VAAAAAJ'><img
src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. 

[//]: # (I have published papers with total <a href='https://scholar.google.)

[//]: # (com/citations?user=6tJ39VAAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> )

[//]: # (&#40;You can also use google scholar badge <a href='https://scholar.google.com/citations?user=6tJ39VAAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>&#41;.)


# 🔥 News
- *2026.11*: &nbsp;🎉🎉 Our paper titled 'Improving Graph Out-of-distribution Generalization Beyond Causality' has been accepted by WSDM-27!
- *2026.08*: &nbsp;The preprint version of our paper titled 'DuMateBench: Evaluating Autonomous Agents in Complex Real-World Workflows' is online.
- *2026.06*: &nbsp;The preprint version of our paper titled 'DuMate-DeepResearch: An Auditable Multi-Agent System with Recursive Search and Rubric-Grounded Reasoning' is online.
- *2026.05*: &nbsp;🎉🎉 Our paper titled 'Adversarial Yet Cooperative: Multi-Perspective Reasoning in Retrieved-Augmented Language Models' has been accepted by ACL-26 (Findings)!
- *2024.09*: &nbsp;🎉🎉 Our paper titled 'Diffusion-based Graph Generative Methods' has been accepted by IEEE Transactions on Knowledge and Data Engineering.
- *2024.05*: &nbsp;🎉🎉 Our paper titled 'Unsupervised Heterogeneous Graph Rewriting Attack via Node Clustering' has been accepted by KDD-24.
- *2024.01*: &nbsp;🎉🎉 The preprint version of our survey titled 'Diffusion-based Graph Generative Methods' is online.
- *2024.01*: &nbsp;🎉🎉 Our paper titled 'Training-free Multi-objective Diffusion Model for 3D Molecule Generation' has been accepted by ICLR-24!
- *2023.12*: &nbsp;🎉🎉 Our paper titled 'Geometric-Facilitated Denoising Diffusion Model for 3D Molecule Generation' has been accepted by AAAI-24!

[//]: # (- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

# 📝 Publications
- ``WSDM-27`` [Improving Graph Out-of-distribution Generalization Beyond Causality](https://arxiv.org/abs/2407.10204). **Can Xu**, Yao Cheng, Jianxiang Yu, Haosen Wang, Jingsong Lv, Yao Liu, Xiang Li.

- ``ACL-26 Findings`` [Adversarial Yet Cooperative: Multi-Perspective Reasoning in Retrieved-Augmented Language Models](https://doi.org/10.18653/v1/2026.findings-acl.1868). **Can Xu**, Lingyong Yan, Jiayi Wu, Haosen Wang, Shuaiqiang Wang, Yuchen Li, Jizhou Huang, Dawei Yin, Xiang Li.

- ``Preprint`` [DuMateBench: Evaluating Autonomous Agents in Complex Real-World Workflows](https://arxiv.org/abs/2608.26546). Zechun Niu, Yukun Zhao, Jiaxin Zhang, Xu Shen, Jinhua Si, Han Tian, **Can Xu**, Yunfan Song, Jiaxin Mao, Yansong Gao, Yuchen Li, Jianmin Wu, Lingyong Yan, Shuaiqiang Wang, Dawei Yin.

- ``Preprint`` [DuMate-DeepResearch: An Auditable Multi-Agent System with Recursive Search and Rubric-Grounded Reasoning](https://arxiv.org/abs/2606.07299). Lingyong Yan, **Can Xu**, Yukun Zhao, Wenxuan Li, Qingyang Chen, Jiulong Wu, Wenli Song, Xiangnan Li, Weixian Shi, Yiqun Chen, Xuchen Ma, Yuchen Li, Jiashu Zhao, Shuaiqiang Wang, Jianmin Wu, Dawei Yin.

- ``FCS`` [A survey on learning from graphs with heterophily: recent advances and future directions](https://doi.org/10.1007/s11704-025-41059-z). Cheng-Hua Gong, Yao Cheng, Jian-Xiang Yu, **Can Xu**, Cai-Hua Shan, Si-Qiang Luo, Xiang Li.

- ``SIGIR-25`` [Enhancing Homophily in Heterogeneous Graph Contrastive Learning via Connection Strength and Multi-view Self-Expression](https://doi.org/10.1145/3726302.3729968). Haosen Wang, Chenglong Shi, **Can Xu**, Surong Yan, Rong Xie, Pan Tang.

- ``ACL-25 Findings`` [Enhancing LLM-based Hatred and Toxicity Detection with Meta-Toxic Knowledge Graph](https://doi.org/10.18653/v1/2025.findings-acl.1270). Yibo Zhao, Jiapeng Zhu, **Can Xu**, Yao Liu, Xiang Li.

- ``TCSS`` [A Structure Redefined Graph Pretraining With Contrastive Prompting for Fake News Detection](https://doi.org/10.1109/tcss.2024.3519657). Haosen Wang, Pan Tang, Linghong Zhou, Chenglong Shi, **Can Xu**, Pengfei Zheng, Surong Yan, Chunqi Wu.

- ``KDD-24`` [Unsupervised Heterogeneous Graph Rewriting Attack via Node Clustering](https://openreview.net/forum?id=mhWoMQ3OBz). Haosen Wang, **Can Xu**, Chenglong Shi,  PengFei Zheng, Shiming Zhang, Minhao Cheng, Hongyang Chen.

- ``TKDE`` [Diffusion-based Graph Generative Methods](https://doi.org/10.1109/TKDE.2024.3466301). Hongyang Chen, **Can Xu**, Lingyu Zheng, Qiang Zhang, Xuemin Lin. (Co-first Author)

- ``ICLR-24`` [Training-free Multi-objective Diffusion Model for 3D Molecule Generation](https://openreview.net/forum?id=X41c4uB4k0). Xu Han, Caihua Shan, Yifei Shen, **Can Xu**, Han Yang, Xiang Li, Dongsheng Li.

- ``AAAI-24`` [Geometric-Facilitated Denoising Diffusion Model for 3D Molecule Generation](https://doi.org/10.1609/aaai.v38i1.27787). **Can Xu**, Haosen Wang, Weigang Wang, Pengfei Zheng, Hongyang Chen. 

- ``Information Sciences`` [A fairness-aware graph contrastive learning recommender framework for social tagging systems](https://www.sciencedirect.com/science/article/pii/S0020025523006497). **Can Xu**, Yin Zhang, Hongyang Chen, Ligang Dong, Weigang Wang.

# 🎖 Honors and Awards
- *2023.10* National Scholarship 
 
# 📖 Educations
- *2021.09 - 2023.12*, Master, Zhejiang Gongshang University, Hangzhou, China
- *2017.09 - 2021.06*, Undergraduate, Nanjing University of Information Science and Technology, Nanjing, China
- *2014.09 - 2017.06*, Suzhou High School, Suzhou, China

[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

# 💻 Internships
- *2022.07 - 2023.08*, Zhejiang Lab, Research Center for Graph Computing, Hangzhou, China.

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

Here is **Lin Li (李琳)**.<br>

I am a postdoctoral fellow in AI Chip Center for Emerging Smart Systems (ACCESS) at the Hong Kong University of Technology and Science (HKUST), advised by [Prof. Kwang-Ting (Tim) Cheng](https://scholar.google.com/citations?user=-SgpaF8AAAAJ&hl=en&oi=ao). Additionally, I collaborate with [Prof. Long Chen](https://zjuchenlong.github.io) at HKUST. Prior to this, I obtained my PhD degree in Computer Science and Technology from Zhejiang University (ZJU), under the supervision of [Prof. Jun Xiao](https://person.zju.edu.cn/junx).<br> 
My research interest includes Multi-modal Large Language Models and Scene Understanding.

If you are interested in any aspect of me, I am always open to discussions and collaborations. Feel free to reach out to me at - lllidy[at]ust.hk


# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/mm25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Compositional zero-shot learning via progressive language-based observations](https://arxiv.org/abs/2311.14749)

**Lin Li**, Guikun Chen, Zhen Wang, Jun Xiao, Long Chen

- Automatically allocating the observation order in the form of primitive concepts or graduated descriptions, enabling effective prediction of unseen state-object compositions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/pami24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Nicest: Noisy label correction and training for robust scene graph generation](https://ieeexplore.ieee.org/abstract/document/10496249)

**Lin Li**, Jun Xiao, Hanrong Shi, Hanwang Zhang, Yi Yang, Wei Liu, Long Chen

[**Code**](https://github.com/HKUST-LongGroup/NICEST)
- A out-of-distribution scene graph generation dataset VG-OOD and a debiased Knowledge distillation strategy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/nips23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Zero-shot visual relation detection via composite visual cues from large language models](https://proceedings.neurips.cc/paper_files/paper/2023/file/9ca825deb6ce588c96f880728d3b8aea-Paper-Conference.pdf)

**Lin Li**, Jun Xiao, Guikun Chen, Jian Shao, Yueting Zhuang, Long Chen

[**Code**](https://github.com/HKUST-LongGroup/RECODE)
- The first exploration of zero-shot visual relation detection via composite description prompts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/iccv23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Compositional feature augmentation for unbiased scene graph generation](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Compositional_Feature_Augmentation_for_Unbiased_Scene_Graph_Generation_ICCV_2023_paper.pdf)

**Lin Li**, Guikun Chen, Jun Xiao, Yi Yang, Chunping Wang, Long Chen

[**Code**](https://github.com/HKUST-LongGroup/CFA)
- Tackling unbiased scene graph generation from the perspective of increasing the diversity of triplet features.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022 Oral</div><img src='images/cvpr22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The devil is in the labels: Noisy label correction for robust scene graph generation](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_The_Devil_Is_in_the_Labels_Noisy_Label_Correction_for_CVPR_2022_paper.pdf)

**Lin Li**, Long Chen, Yifeng Huang, Zhimeng Zhang, Songyang Zhang, Jun Xiao

[**Code**](https://github.com/muktilin/NICE)
- Reformulating scene graph generation (SGG) as a noisy label learning problem, and pointing out that the two plausible assumptions are not applicable for SGG.
</div>
</div>


(†: Corresponding author, *: Equal contribution, ♢: Student first author)


- `ACM MM 2025` [Zero-shot compositional action recognition with neural logic constraints.]() Gefan Ye\*, **Lin Li\*†**, Kexin Li\*, Jun Xiao, Long Chen

- `CVPR 2025 Highlight` [Comm: A coherent interleaved image-text dataset for multimodal understanding and generation.](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Chen_CoMM_A_Coherent_CVPR_2025_supplemental.pdf) Wei Chen\*, **Lin Li\***, Yongqi Yang*, Bin Wen, Fan Yang, Tingting Gao, Yu Wu, Long Chen

- `PR 2025` [Knowledge Integration for Grounded Situation Recognition.](https://www.sciencedirect.com/science/article/abs/pii/S0031320325004261) Jiaming Lei, Sijing Wu, **Lin Li†**, Lei Chen, Jun Xiao, Yi Yang, Long Chen

- `ACM MM 2024` [Seeing beyond classes: Zero-shot grounded situation recognition via language explainer.](https://dl.acm.org/doi/abs/10.1145/3664647.3681036) Jiaming Lei, **Lin Li†**, Chunping Wang, Jun Xiao, Long Chen

- `IJCV 2024` [From easy to hard: Learning curricular shape-aware features for robust panoptic scene graph generation.](https://link.springer.com/article/10.1007/s11263-024-02190-9) Hanrong Shi\*, **Lin Li\*†**, Jun Xiao, Yueting Zhuang, Long Chen.

- `TCSVT 2023` [Label semantic knowledge distillation for unbiased scene graph generation.](https://ieeexplore.ieee.org/abstract/document/10143319) **Lin Li**, Jun Xiao, Hanrong Shi, Wenxiao Wang, Jian Shao, An-An Liu, Yi Yang, Long Chen.

- `ESWA 2023` [Question-guided feature pyramid network for medical visual question answering.](https://www.sciencedirect.com/science/article/abs/pii/S0957417422021662) Yonglin Yu, Haifeng Li, Hanrong Shi, **Lin Li†** 

- `ACM MM 2021 Oral` [Instance-wise or class-wise? a tale of neighbor shapley for concept-based explanation.](https://dl.acm.org/doi/abs/10.1145/3474085.3475337) Jiahui Li, Kun Kuang, **Lin Li**, Long Chen, Songyang Zhang, Jian Shao, Jun Xiao


- `TMM 2020` [Explore video clip order with self-supervised and curriculum learning for video applications.](https://ieeexplore.ieee.org/abstract/document/9204376)<br>Jun Xiao, **Lin Li♢**, Dejing Xu, Chengjiang Long, Jian Shao, Shifeng Zhang, Shiliang Pu, Yueting Zhuang



# 🎖 Honors and Awards
- *2023.10* Academic Star Training Program for Doctoral Students in Zhejiang University.
- *2022.09* Transfar Group Scholarship at Zhejiang University.
- *2021.09* National Scholarship.
- *2017.09* National Scholarship.


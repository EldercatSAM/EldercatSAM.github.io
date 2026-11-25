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

Hi! Welcome to my homepage. I'm **Siran Dai (戴思然)**, a final-year Ph.D. student at the Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS), supervised by [Qingming Huang (&#40644;&#24198;&#26126;)](http://people.ucas.ac.cn/~qmhuang) (Professor at UCAS; IEEE Fellow) and [Qianqian Xu (许倩倩)](https://qianqianxu010.github.io/) (Professor at ICT, CAS). I received a B.E. in Robotics Engineering from BJUT in 2022. I am currently a research intern at the [Beijing Academy of Artificial Intelligence (BAAI)](https://www.baai.ac.cn/), working on AI agents.

My research interests include:
- **Vision Foundation Models and Representation Learning**: understanding and improving the structure of dense representations of self-supervised vision foundation models.
- **Temporal State Modeling and Physical AI**: temporally consistent, state-aware visual representations for latent world models and robotic manipulation.
- **AI Agents**: test-time self-evolving agents and the evaluation of long-horizon web agents.

# 🔥 News
- *2026.11*: One paper is accepted by TPAMI.
- *2026.09*: One paper (CODI) is accepted by NeurIPS 2026.
- *2026.06*: Won 1st and 2nd place in the CVPR 2026 DataMFM Challenge.
- *2026.03*: Two papers are accepted by CVPR 2026.
- *2025.11*: One paper is accepted by AAAI 2026.
- *2025.09*: One paper is accepted by NeurIPS 2025.
- *2025.09*: One paper is accepted by TPAMI.
- *2025.06*: Won first place in the CVDD and AVA workshops at CVPR 2025.
- *2025.02*: One paper is accepted by CVPR 2025.
- *2024.10*: Our paper "Not All Pairs are Equal: Hierarchical Learning for Average-Precision-Oriented Video Retrieval" received an Honourable Mention Award at ACM MM 2024.
- *2024.07*: Two papers are accepted by ACM MM 2024.
- *2023.09*: One paper is accepted by NeurIPS 2023.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/papers/neurips26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CODI: Improving Self-Supervised Vision Transformers with Cross Distillation](https://arxiv.org/abs/2610.30639)

**Siran Dai**, Qianqian Xu, Peisong Wen, Yang Liu, Xiaochun Cao, Qingming Huang. Annual Conference on Neural Information Processing Systems (**NeurIPS**) 2026. [\[Code\]](https://github.com/EldercatSAM/CODI)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/papers/neurips25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Structural Degradation in Dense Representations for Self-supervised Learning](https://arxiv.org/abs/2510.17299)

**Siran Dai**, Qianqian Xu, Peisong Wen, Yang Liu, Qingming Huang. Annual Conference on Neural Information Processing Systems (**NeurIPS**) 2025. [\[Code\]](https://github.com/EldercatSAM/SSL-Degradation)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/papers/neurips23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DRAUC: An Instance-wise Distributionally Robust AUC Optimization Framework](https://arxiv.org/pdf/2311.03055)

**Siran Dai**, Qianqian Xu, Peisong Wen, Yang Liu, Qingming Huang. Annual Conference on Neural Information Processing Systems (**NeurIPS**) 2023. [\[Code\]](https://github.com/EldercatSAM/DRAUC)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/papers/cvpr26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Static to Dynamic: Exploring Self-supervised Image-to-Video Representation Transfer Learning](https://arxiv.org/abs/2603.26597)

Yang Liu, Qianqian Xu, Peisong Wen, **Siran Dai**, Xilin Zhao, Qingming Huang. IEEE/CVF Computer Vision and Pattern Recognition Conference (**CVPR**), 2026. [\[Code\]](https://github.com/yafeng19/Co-Settle)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/papers/pami25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Semantic Concentration for Self-Supervised Dense Representation Learning](https://arxiv.org/abs/2509.09429)

Peisong Wen, Qianqian Xu, **Siran Dai**, Runmin Cong, Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2025. [\[Code\]](https://github.com/KID-7391/CoTAP)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/papers/cvpr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When the future becomes the past: Taming temporal correspondence for self-supervised video representation learning](https://openaccess.thecvf.com/content/CVPR2025/papers/Liu_When_the_Future_Becomes_the_Past_Taming_Temporal_Correspondence_for_CVPR_2025_paper.pdf)

Yang Liu, Qianqian Xu, Peisong Wen, **Siran Dai**, Qingming Huang. IEEE/CVF Computer Vision and Pattern Recognition Conference (**CVPR**), 24033-24044, 2025. [\[Code\]](https://github.com/yafeng19/T-CORE)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024 (Honourable Mention Award)</div><img src='images/papers/acmmm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Not All Pairs are Equal: Hierarchical Learning for Average-Precision-Oriented Video Retrieval](https://arxiv.org/pdf/2407.15566)

Yang Liu, Qianqian Xu, Peisong Wen, **Siran Dai**, Qingming Huang. ACM International Conference on Multimedia (**ACM MM**), 3828-3837, 2024. [\[Code\]](https://github.com/yafeng19/HAP-VR)

</div>
</div>

[Safe Codebook: Token-Level Moderation for Safer Visual Autoregressive Generation](https://openaccess.thecvf.com/content/CVPR2026F/html/Zhang_Safe_Codebook_Token-Level_Moderation_for_Safer_Visual_Autoregressive_Generation_CVPRF_2026_paper.html), Jiaxuan Zhang, Qianqian Xu, Peisong Wen, **Siran Dai**, Yang Liu, Qingming Huang. IEEE/CVF Computer Vision and Pattern Recognition Conference Findings (**CVPR Findings**), 7924-7934, 2026.

[HiGFA: Hierarchical Guidance for Fine-grained Data Augmentation with Diffusion Models](https://arxiv.org/pdf/2511.12547), Zhiguang Lu, Qianqian Xu, Peisong Wen, **Siran Dai**, Qingming Huang. Annual AAAI Conference on Artificial Intelligence (**AAAI**), 2026.

[Self-supervised Representation Learning with Local Aggregation for Image-based Profiling](https://arxiv.org/abs/2506.14265), **Siran Dai**, Qianqian Xu, Peisong Wen, Yang Liu, Qingming Huang. CVPR Workshop on Computer Vision for Drug Discovery (**CVPRW**), 2025.

[Regularized contrastive partial multi-view outlier detection](https://dl.acm.org/doi/pdf/10.1145/3664647.3681125), Yijia Wang, Qianqian Xu, Yangbangyan Jiang, **Siran Dai**, Qingming Huang. ACM International Conference on Multimedia (**ACM MM**), 8711-8720, 2024.

[Slot-JEPA: Object-Structured Prediction Interfaces for Latent World Models](https://arxiv.org/abs/2610.28074), Peisong Wen, Qianqian Xu, Minye Lei, **Siran Dai**, Yang Liu, Qingming Huang. arXiv preprint arXiv:2610.28074, 2026.

[MobileDreamer: Generative Sketch World Model for GUI Agent](https://arxiv.org/abs/2601.04035), Yilin Cao, Yufeng Zhong, Zhixiong Zeng, **Siran Dai**, Liming Zheng, Jing Huang, Haibo Qiu, Peng Shi, Wenji Mao. arXiv preprint arXiv:2601.04035, 2026.


# 🎖 Honors and Awards
- *2026.06*: 1st and 2nd place in the CVPR 2026 DataMFM Challenge (Document Parsing), hosted by MIT-IBM.
- *2025.06*: First place in [CVPR 2025 AVA Challenge of 3D Human Motion Generation Track](https://accessibility-cv.github.io/).
- *2025.05*: First place in [CVPR 2025 Cell Line Transferability Challenge](https://cvdd-cvpr25.github.io/challenge.html).
- *2024.10*: ACM MM 2024 Honourable Mention Award.
- *2021.10*: Xiaomi Special Scholarship (10 recipients university-wide).
- *2021.08*: Silver Medal (Top 1%) in the Kaggle CommonLit Readability Prize.
- *2020.10*: Xiaomi Special Scholarship (10 recipients university-wide).
- *2020.10*: National Scholarship.


# 📖 Services
- Reviewer for NeurIPS 24/25/26
- Reviewer for ICLR 24/25/26/27
- Reviewer for ICML 26
- Reviewer for CVPR 26/27
- Reviewer for ECCV 26
- Reviewer for KDD 26
- Reviewer for AISTATS 24/25/26/27
- Reviewer for TPAMI/TMLR/TCSVT/TMM

# 🎓 Education

- *2022.09 - Now*, Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS), Ph.D. student in Computer Applied Technology.
- *2018.09 - 2022.07*, Beijing University of Technology (BJUT), B.E. in Robotics Engineering.

# 💻 Internships

- *2026.05 - Now*, [Beijing Academy of Artificial Intelligence (BAAI)](https://www.baai.ac.cn/), Research Intern on AI Agents. 


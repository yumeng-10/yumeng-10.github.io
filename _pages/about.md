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

I am a first-year PhD student at UIUC CS, supervised by Prof. [Ge Wang](https://tiffanygewang.com/). Previously, I was fortunate to work with Prof. [May Fung](https://yrf1.github.io/), Prof. [Heng Ji](https://blender.cs.illinois.edu/hengji.html), Prof. [Xiaojuan Ma](https://www.cse.ust.hk/~mxj/), Prof. [Yangqiu Song](https://www.cse.ust.hk/~yqsong/), and Prof. [Hao Chen](https://cse.hkust.edu.hk/~jhc/).

My research interest lies in the intersection of NLP and HCI. I aim to empower human-centered NLP by mitigating LLM bias, leveraging scalable alignment. I also want to understand the socio-cultural dynamics of LLM by incorporating methods and theories from HCI.


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
- 🎉 Our paper *CoKnowledge: Supporting Assimilation of Time-synced Collective Knowledge in Online Science Videos* is accepted by CHI 2025! Thanks to my amazing mentors Prof. Ma, Yuanhao and my coolest collaborators!
- 🎉 My first-authored paper *CALM: Unleashing the Cross-Lingual Self-Aligning Ability of Language Model Question Answering* is accepted by NAACL 2025! Big shout out to my mentors Heng, Yi, Qingyun and Zhiyuan!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/multirole-r1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Diversity-Enhanced Reasoning for Subjective Questions](https://arxiv.org/abs/2507.20187)

**Yumeng Wang\***, Zhiyuan Fan\*, Jiayu Liu\*, May Fung

- We propose **MultiRole-R1**, a diversity-enhanced framework with multiple role perspectives, to improve the accuracy and diversity in subjective reasoning tasks. MultiRole-R1 features an unsupervised data construction pipeline that generates reasoning chains that incorporate diverse role perspectives. We further employ reinforcement learning via Group Relative Policy Optimization (GRPO) with reward shaping, by taking diversity as a reward signal in addition to the verifiable reward.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/v2r.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unveiling the Lack of LVLM Robustness to Fundamental Visual Variations: Why and Path Forward
](https://arxiv.org/abs/2507.20187)

Zhiyuan Fan\*, **Yumeng Wang\***, Sandeep Polisetty, May Fung

- Large Vision Language Models (LVLMs) excel in various vision-language tasks. Yet, their robustness to visual variations in position, scale, orientation, and context that objects in natural scenes inevitably exhibit due to changes in viewpoint and environment remains largely underexplored. To bridge this gap, we introduce V2R-Bench, a comprehensive benchmark framework for evaluating Visual Variation Robustness of LVLMs, which encompasses automated evaluation dataset generation and principled metrics for thorough robustness assessment.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2025</div><img src='images/teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoKnowledge: Supporting Assimilation of Time-synced Collective Knowledge in Online Science Videos](https://arxiv.org/abs/2502.03767)

Yuanhao Zhang, **Yumeng Wang**, Xiyuan Wang, Changyang He, Chenliang Huang, Xiaojuan Ma

- We propose a web demo to develop CoKnowledge – a tool incorporating a video abstract, knowledge graphs, and supplementary danmaku features to support viewers’ assimilation of collective knowledge in science videos.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025</div><img src='images/CALM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CALM: Unleashing the Cross-Lingual Self-Aligning Ability of Language Model Question Answering](https://arxiv.org/abs/2501.18457)

**Yumeng Wang**, Zhiyuan Fan, Qingyun Wang, May Fung, Heng Ji

[**Github**](https://github.com/yumeng-10/CALM) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a self consistency based multilingual alignment algorithm to bridge the knowledge gap across different languages. We evaluate this method under both zero-shot chain-of-thought and retrieval augmented setting.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/donet_figure1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DoNet: Deep De-Overlapping Network for Cytology Instance Segmentation**

Hao Jiang\*, Rushan Zhang\*, Yanning Zhou, **Yumeng Wang**, Hao Chen

[**Google Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=72yDElgAAAAJ&citation_for_view=72yDElgAAAAJ:u5HHmVD_uO8C&inst=7707536466893209563) |
[**Paper**](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_DoNet_Deep_De-Overlapping_Network_for_Cytology_Instance_Segmentation_CVPR_2023_paper.pdf) |
[**Code**](https://github.com/DeepDoNet/DoNet) |
<strong><span class='show_paper_citations' data='72yDElgAAAAJ:u5HHmVD_uO8C'></span></strong>
- In this work, we proposed a De-overlapping Network (DoNet) in a decompose-and-recombined strategy. A Dual-path Region Segmentation Module (DRM) explicitly decomposes the cell clusters into intersection and complement regions, followed by a Semantic Consistency-guided Recombination Module (CRM) for integration. To further introduce the containment relationship of the nucleus in the cytoplasm, we design a Mask-guided Region Proposal Strategy (MRP) that integrates the cell attention maps for inner-cell instance prediction.

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- HKUST Engineering Dean's List
- HKUST Congtinuing Undergraduate Scholarship
- HKUST Study Abroad Scholarship
# 📖 Educations
- Hong Kong University of Science and Technology, major in COMP + DSCT (BEng). 
- University of Illinois Urbana-Champaign, Grainger School of Engineering (Exchange). 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.01 - 2023.08*, [WeShare Tech Limited](https://www.wesharetechnology.com/), HKUST.
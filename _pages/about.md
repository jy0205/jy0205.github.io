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

I am Yang Jin (金阳), a Ph.D. student at Wangxuan Institute of Computer Technology (WICT) in Peking University, advised by [Prof. Yadong Mu](http://www.muyadong.com/). Before that, I obtained my B.S. degree in Computer Science and Engineering from Beihang University. I have been a research intern at [ByteDance](https://www.bytedance.com/en/) and [Kuaishou Technology](https://www.kuaishou.com/en/).

My research interests cover (1) **Multi-modal Large Language Model** and large-scale vision-language pre-training (2) **AIGC** including image, video, and personalized generation with both diffusion and autoregressive models (3) **Video Understanding** covers both recognition and localization tasks. I have published several papers and been reviewers at many conferences such as CVPR, ECCV, ICCV. If you are interested in my research, feel free to contact me through e-mail.


# 🔥 News
- *2025.01*: One paper is accepted at ICLR 2025!
- *2024.09*: One paper is accepted at NeurIPS 2024!
- *2024.07*: One paper is accepted at ECCV 2024!
- *2024.05*: One paper is accepted at ICML 2024 as an Oral presentation!
- *2024.01*: One paper is accepted at ICLR 2024!
- *2023.07*: One paper is accepted at ICCV 2023!
- *2023.03*: One paper is accepted at CVPR 2023!
- *2022.09*: One paper is accepted at NeurIPS 2022 as a spotlight presentation!
- *2022.03*: One paper is accepted at CVPR 2022!
- *2021.04*: One paper is accepted at TMM 2021!
  

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/pyramid_flow.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ICLR 2025**] [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://arxiv.org/abs/2410.05954)

**Yang Jin**, Zhicheng Sun, Ningyuan Li, Kun Xu, Kun Xu, Hao Jiang, Nan Zhuang, Quzhe Huang, Yang Song, Yadong Mu, Zhouchen Lin

[**[Paper]**](https://arxiv.org/pdf/2410.05954) [**[Project]**](https://pyramid-flow.github.io/) [**[Code]**](https://github.com/jy0205/Pyramid-Flow)
- We design a unified flow matching objective that jointly generates and decompresses visual content across pyramidal representations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024 Oral</div><img src='images/video_lavit.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ICML 2024 Oral**] [Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization](https://arxiv.org/abs/2402.03161)

**Yang Jin**, Zhicheng Sun, Kun Xu, Kun Xu, Liwei Chen, Hao Jiang, Quzhe Huang, Chengru Song, Yuliang Liu, Di Zhang, Yang Song, Kun Gai, Yadong Mu

[**[Paper]**](https://arxiv.org/pdf/2402.03161.pdf) [**[Project]**](https://video-lavit.github.io) [**[Code]**](https://github.com/jy0205/LaVIT)
- We present a multimodal LLM capable of both comprehending and generating videos, based on an efficient decomposed video representation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/LaVIT_fig.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ICLR 2024**] [Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization](https://arxiv.org/abs/2309.04669)

**Yang Jin**, Kun Xu, Kun Xu, Liwei Chen, Chao Liao, Jianchao Tan, Quzhe Huang, Bin Chen, Chenyi Lei, An Liu, Chengru Song, Xiaoqiang Lei, Di Zhang, Wenwu Ou, Kun Gai, Yadong Mu

[**[Paper]**](https://arxiv.org/pdf/2309.04669.pdf) [**[Code]**](https://github.com/jy0205/LaVIT)
- We present an effective dynamic discrete visual tokenizer that represents an image as the foreign language in Large Language Models, which supports both multi-modal understanding and generation.
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/RectifID.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NeurIPS 2024**] [RectifID: Personalizing Rectified Flow with Anchored Classifier Guidance](https://arxiv.org/abs/2405.14677)

Zhicheng Sun, Zhenhao Yang, **Yang Jin**, Haozhe Chi, Kun Xu, Kun Xu, Liwei Chen, Hao Jiang, Di Zhang, Yang Song, Kun Gai, Yadong Mu

[**[Paper]**](https://arxiv.org/pdf/2405.14677) [**[Code]**](https://github.com/feifeiobama/RectifID)
- We introduce a training-free approach to personalizing rectified flow, based on a fixed-point formulation of classifier guidance.
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/ECLIP.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**CVPR 2023**] [Learning Instance-Level Representation for Large-Scale Multi-Modal Pretraining in E-commerce](https://arxiv.org/abs/2304.02853)

**Yang Jin**, Yongzhi Li, Zehuan Yuan, Yadong Mu

[**[Paper]**](https://arxiv.org/pdf/2304.02853.pdf)
- We propose a generic multi-modal foundation model in E-commerce that learns the instance-level representation of products and achieves superior performance on massive downstream E-commerce applications. 
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022 Spotlight</div><img src='images/video_grounding.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NeurIPS 2022 Spotlight**] [Embracing Consistency: A One-Stage Approach for Spatio-Temporal Video Grounding](https://arxiv.org/abs/2209.13306)

**Yang Jin**, Yongzhi Li, Zehuan Yuan, Yadong Mu

[**[Paper]**](https://arxiv.org/pdf/2209.13306.pdf) [**[Code]**](https://github.com/jy0205/STCAT)
- We propose STCAT, a new one-stage spatio-temporal video grounding model that enjoys more consistent cross-modal feature alignment and tube prediction. It also achieved state-of-the-art performance on VidSTG and HC-STVG benchmarks. 
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/MLN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**CVPR 2022**] [Complex Video Action Reasoning via Learnable Markov Logic Network](https://openaccess.thecvf.com/content/CVPR2022/html/Jin_Complex_Video_Action_Reasoning_via_Learnable_Markov_Logic_Network_CVPR_2022_paper.html)

**Yang Jin**, Linchao Zhu, Yadong Mu

[**[Paper]**](https://openaccess.thecvf.com/content/CVPR2022/papers/Jin_Complex_Video_Action_Reasoning_via_Learnable_Markov_Logic_Network_CVPR_2022_paper.pdf)
- We devise an video action reasoning framework that performs Markov Logic Network (MLN) based probabilistic logical inference. The proposed framework enjoys remarkable interpretability through the learned logical rules.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2021</div><img src='images/TMM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**TMM 2021**] [Zero-Shot Video Event Detection with High-Order Semantic Concept Discovery and Matching](https://ieeexplore.ieee.org/abstract/document/9405453/)

**Yang Jin**, Wenhao Jiang, Yi Yang, Yadong Mu

[**[Paper]**](https://ieeexplore.ieee.org/abstract/document/9405453/)
- We design an effective zero-shot video event retrieval framework based on the utilization of high-order concepts (such as subject-predicate-object triplets or adjective-object). The constructed high-order concept library and proposed query-expanding scheme significantly improved the perfromance.
  
</div>
</div>


- [Video Action Segmentation via Contextually Refined Temporal Keypoints](https://openaccess.thecvf.com/content/ICCV2023/papers/Jiang_Video_Action_Segmentation_via_Contextually_Refined_Temporal_Keypoints_ICCV_2023_paper.pdf), Borui Jiang, **Yang Jin**, Zhentao Tan, Yadong Mu, **ICCV 2023**
  
- [Beyond Short-Term Snippet: Video Relation Detection with Spatio-Temporal Global Context](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Beyond_Short-Term_Snippet_Video_Relation_Detection_With_Spatio-Temporal_Global_Context_CVPR_2020_paper.pdf), Chenchen Liu, **Yang Jin**, Kehan Xu, Guoqiang Gong, Yadong Mu, **CVPR 2020**


# 🎖 Honors and Awards
- Peking University President's Scholarship
- Wang Xuan Scholarship
- Peking University Study Excellence Award
- Peking University Excellent Research Award


# 📖 Educations
- *2020.09 - 2025.07 (expected)*, Ph.D. Student, [Academy for Advanced Interdisciplinary Studies](http://www.aais.pku.edu.cn/), Peking University.
- *2016.09 - 2020.07*,            Undergraduate Student, [School of Computer Science and Engineering](https://scse.buaa.edu.cn/English/Home.htm) (SCSE), Beihang University. 


# 💻 Internships
- *2023.07 - now*,     Content Understanding and Generation Group, Kuaishou Technology, China.
- *2022.04 - 2023.06*, Content Understanding Group, ByteDance, China.


# 🏫 Professional Services
- Reviewer for CVPR 2023, CVPR 2024, ICCV 2023, ECCV 2024.

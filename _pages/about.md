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

My research interests cover visual grounding, multi-modal learning, and generative models. Recently, my work mainly focus on developing effective multi-modal large language models. I have published several papers and been reviewer at many conferences such as CVPR, ECCV, ICCV, and NeurIPS. If you are interested in my research, feel free to contact me through e-mail.


# 🔥 News
- *2024.01*: One paper is accepted at ICLR 2024!
- *2023.07*: One paper is accepted at ICCV 2023!
- *2023.03*: One paper is accepted at CVPR 2023!
- *2022.09*: One paper is accepted at NeurIPS 2022 as a spotlight presentation!
- *2022.03*: One paper is accepted at CVPR 2022!
- *2021.04*: One paper is accepted at TMM 2021!
  

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/video_lavit.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization](https://arxiv.org/abs/2402.03161)

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
- We present an effective dynamic visual tokenizer that represents an image as the foreign language in LLM, which supports both multi-modal understanding and generation.
  
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
- We propose STCAT, a new one-stage spatio-temporal video grounding method, which achieved state-of-the-art performance on VidSTG and HC-STVG benchmarks. 
  
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

- [Zero-Shot Video Event Detection with High-Order Semantic Concept Discovery and Matching](https://ieeexplore.ieee.org/document/9405453), **Yang Jin**, Wenhao Jiang, Yi Yang, Yadong Mu, **TMM 2021**

- [Video Action Segmentation via Contextually Refined Temporal Keypoints](https://openaccess.thecvf.com/content/ICCV2023/papers/Jiang_Video_Action_Segmentation_via_Contextually_Refined_Temporal_Keypoints_ICCV_2023_paper.pdf), Borui Jiang, **Yang Jin**, Zhentao Tan, Yadong Mu, **ICCV 2023**
  
- [Beyond Short-Term Snippet: Video Relation Detection with Spatio-Temporal Global Context](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Beyond_Short-Term_Snippet_Video_Relation_Detection_With_Spatio-Temporal_Global_Context_CVPR_2020_paper.pdf), Chenchen Liu, **Yang Jin**, Kehan Xu, Guoqiang Gong, Yadong Mu, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

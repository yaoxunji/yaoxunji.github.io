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

<!-- Jixun Yao -->

I’m a four-year Ph.D. student at the Northwestern Polytechnical University, supervised by Prof. [Lei Xie](http://lxie.npu-aslp.org/).


<!-- My research interest includes speech synthesis, voice conversion and speaker anonymization. I have published more than 20 papers at the top international speech conferences and journal with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

My research interest includes speech synthesis, voice conversion and speaker anonymization. I have published more than 20 papers at the top international speech conferences and journal.

# 🔍 Research Area
**Speech Processing**: Voice Conversion, Text-to-Speech, Speaker Anonymization, Expressive Speech Synthesis

**Large Language Models**: Speech LLMs, Speech Tokenizer, Diffusion Models

<!-- **Speech Privacy**: -->

# 💻 Internships
- *2024.03 - Now*, Nanyang Technological University, Singapore (supervised by Prof. [Eng-Siong Chng](https://aseschng.github.io/intro1.html)).
- *2022.12 - 2024.02*, Everest Team - Ximalaya, China.

<!-- # 🔥 News
- *2024.03*: &nbsp;🎉🎉 I exchange to Nanyang Technological University supervised by Prof. [Eng-Siong Chng](https://aseschng.github.io/intro1.html). -->

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

2024:

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE TASLP</span> Distinctive and Natural Speaker Anonymization via Singular Value Transformation-Assisted Matrix. **J Yao**, Y Lei, Q Wang, P Guo, Z Ning, L Xie. [[PDF]](https://arxiv.org/pdf/2405.10786) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2024</span> PromptVC: Flexible stylistic voice conversion in latent space driven by natural language prompts. **J Yao**, Y Yang, Y Lei, Z Ning, Y Hu, Y Pan, J Yin, H Zhou, H Lu, L Xie. [[PDF]](https://arxiv.org/pdf/2309.09262)  [[DemoPage]](https://yaoxunji.github.io/prompt_vc/)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2024</span> Dualvc 2: Dynamic masked convolution for unified streaming and non-streaming voice conversion. Z Ning, Y Jiang, P Zhu, S Wang, **J Yao**, L Xie, M Bi. [[PDF]](https://arxiv.org/pdf/2309.15496)  [[DemoPage]](https://dualvc.github.io/dualvc2/)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2024</span> GEmo-CLAP: Gender-Attribute-Enhanced Contrastive Language-Audio Pretraining for Accurate Speech Emotion Recognition. Y Pan, Y Hu, Y Yang, W Fei, **J Yao**, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2306.07848) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">INTERSPEECH 2024</span> DualVC 3: Leveraging Language Model Generated Pseudo Context for End-to-end Low Latency Streaming Voice Conversion. Z Ning, S Wang, P Zhu, Z Wang, **J Yao**, L Xie, M Bi. [[PDF]](https://arxiv.org/pdf/2406.07846)  [[DemoPage]](https://nzqian.github.io/dualvc3/)

2023:
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span> Preserving background sound in noise-robust voice conversion via multi-task learning. **J Yao**, Y Lei, Q Wang, P Guo, Z Ning, L Xie, H Li, J Liu, D Xie. [[PDF]](https://arxiv.org/pdf/2211.03036)  [[DemoPage]](https://yaoxunji.github.io/background_sound_vc/)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span> Distinguishable speaker anonymization based on formant and fundamental frequency scaling. **J Yao**, Q Wang, Y Lei, P Guo, L Xie, N Wang, J Liu. [[PDF]](https://arxiv.org/pdf/2211.03038) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span> Expressive-vc: Highly expressive voice conversion with attention fusion of bottleneck and perturbation features. Z Ning, Q Xie, P Zhu, Z Wang, L Xue, **J Yao**, L Xie, M Bi. [[PDF]](https://arxiv.org/pdf/2211.04710)  [[DemoPage]](https://nzqian.github.io/Expressive-VC.github.io/)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE TASLP</span> Timbre-reserved Adversarial Attack in Speaker Identification. Q Wang, **J Yao**, L Zhang, P Guo, L Xie. [[PDF]](https://arxiv.org/pdf/2309.00929) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ASRU 2023</span> Salt: Distinguishable Speaker Anonymization Through Latent Space Transformation. Y Lv, **J Yao**, P Chen, H Zhou, H Lu, L Xie. [[PDF]](https://arxiv.org/pdf/2310.05051) [[Code]](https://github.com/BakerBunker/SALT)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">INTERSPEECH 2023</span> Pseudo-Siamese Network based Timbre-reserved Black-box Adversarial Attack in Speaker Identification. Q Wang, **J Yao**, Z Wang, P Guo, L Xie. [[PDF]](https://arxiv.org/pdf/2305.19020) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">INTERSPEECH 2023</span> Dualvc: Dual-mode voice conversion using intra-model knowledge distillation and hybrid predictive coding. Z Ning, Y Jiang, P Zhu, **J Yao**, S Wang, L Xie, M Bi. [[PDF]](https://arxiv.org/pdf/2305.12425) [[DemoPage]](https://dualvc.github.io/) 


- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">AAAI 2023</span> UniSyn: an end-to-end unified model for text-to-speech and singing voice synthesis. Y Lei, S Yang, X Wang, Q Xie, **J Yao**, L Xie, D Su. [[PDF]](https://arxiv.org/pdf/2212.01546) [[DemoPage]](https://leiyi420.github.io/UniSyn/) 


- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">DADA@IJCAI 2023</span> The NPU-ASLP System for Deepfake Algorithm Recognition in ADD 2023 Challenge. Z Wang, Q Wang, **J Yao**, L Xie. [[PDF]](http://addchallenge.cn/files/2023/pdf/p64-wang.pdf) 


- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">SMAC 2023</span> Exploring the power of cross-contextual large language model in mimic emotion prediction. G Yi, Y Yang, Y Pan, Y Cao, **J Yao**, X Lv, C Fan, Z Lv, J Tao, S Liang, H Lu. [[PDF]](https://dl.acm.org/doi/10.1145/3606039.3613109) 


2022:

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">VPC 2022</span> NWPU-ASLP system for the voiceprivacy 2022 challenge. **J Yao**, Q Wang, L Zhang, P Guo, Y Liang, L Xie. [[PDF]](https://arxiv.org/pdf/2209.11969) 


# 🎖 Honors and Awards
- *2023.06* The 4th place winner for the Deepfake Algorithm Recognition task in the Audio Deepfake Detection (ADD) Challenge @ IJCAI Workshop, 2023. 
- *2022.09* The 1th place winner in the VoicePrivacy Challenge (VPC) 2022 @ INTERSPEECH Workshop, 2024


<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 💬 Service
- Reviewer
  - IEEE TASLP
  - IEEE SPL
  - Speech Communication
  - ICASSP `2024
  - INTERSPEECH `2024
  - ACM MM `2024
- Organizer
  - [Conversational Voice Clone Challenge (CoVoC)](https://www.magicdatatech.com/iscslp-2024) @ ISCSLP 2024

Thanks for the template of [acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io)
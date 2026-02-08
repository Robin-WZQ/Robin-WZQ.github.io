---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


<span class='anchor' id='about-me'></span>

# About me <img align=center src="https://user-images.githubusercontent.com/26017543/213809353-c908d93c-3dff-4694-9d13-e0e5cbdb879c.png" alt="Waving Hand" width="36" height="36" />
> Ideas are cheap, engineering is all you need.

Hi! Welcome to my homepage. I’m **Zhongqi Wang (王中琦)**, a Third-year PhD candidate with the Institute of Computing Technology (ICT), Chinese Academy of Sciences (CAS). Now I am under the supervision of Prof. [Shiguang Shan](https://vipl.ict.ac.cn/people/~sgshan) and work closely with Prof. [Jie Zhang](https://vipl.ict.ac.cn/people/jzhang/) and Prof. [Xilin Chen](https://vipl.ict.ac.cn/people/xlchen/). My research interests cover computer vision, pattern recognition, machine learning, particularly include backdoor attacks and defenses, model evaluation, AI safety and trustworthiness. 

# 🔥 News
- _2025.11_: &nbsp; 🎉🎉🎉: One paper on backdoor detection is accepted by IEEE TPAMI.

- _2025.10_: &nbsp; I was awarded the National Scholarship for Master Students.

- _2025.02_: &nbsp; 🎉🎉: One paper on model evaluation is accepted by ICLR 2025.

- _2024.12_: &nbsp; I received the Huawei Master Scholarship in 2024.

- _2024.06_: &nbsp; 🎉🎉: One paper on backdoor defense is accepted by ECCV 2024.

- _2023.04_: &nbsp; 🎉: One paper on image generation is accepted by ICME 2023 (Oral).

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/DAA_TPAMI2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Attention Analysis for Backdoor Detection in Text-to-Image Diffusion Models](https://ieeexplore.ieee.org/document/11300728)
 
  **Zhongqi Wang**, Jie Zhang, Shiguang Shan, Xilin Chen.
- We propose a novel backdoor detection method based on Dynamic Attention Analysis (DAA), which sheds light on dynamic anomalies of cross-attention maps in backdoor samples.
- We introduce two progressive methods, *i.e.*, DAA-I and DAA-S, to extract features and quantify dynamic anomalies. 
- Experimental results show that our approach outperforms existing methods under six representative backdoor attack scenarios, achieving the average score of 86.27% AUC.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR</div><img src='images/Dysca_ICLR2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dysca: A Dynamic and Scalable Benchmark for Evaluating Perception Ability of LVLMs](https://openreview.net/forum?id=bU1JOvdXXK)
 
 Jie Zhang, **Zhongqi Wang**, Mengqi Lei, Zheng Yuan, Bei Yan, Shiguang Shan, Xilin Chen. (Student first author)
- A benchmark that is able to dynamically generate the test data that users need and is easily to scale up to to new subtasks and scenarios.
- Dysca aims to testing LVLMs’ performance on diverse styles, 4 image scenarios and 3 question types, reporting the 20 perceptual subtasks performance of 26 mainstream LVLMs,
including GPT-4o and Gemini-1.5-Pro.
- We demonstrate for the first time that evaluating LVLMs using large-scale synthetic data is valid.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV</div><img src='images/ECCV24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T2IShield: Defending against backdoors on text-to-image diffusion models](https://link.springer.com/chapter/10.1007/978-3-031-73013-9_7)
 
 **Zhongqi Wang**, Jie Zhang, Shiguang Shan, Xilin Chen.
- The first backdoor defense method for Text-to-image diffusion models.
- We show the "Assimilation Phenomenon" in the backdoor samples.
- By analyzing the structural correlation of attention maps, we propose two detection techniques: Frobenius Norm Threshold Truncation and Covariance Discriminant Analysis.
- Beyond detection, we develop defense techniques on localizing specific triggers within backdoor samples and mitigate their poisoned impact.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME</div><img src='images/CCLAP_ICME23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CCLAP: Controllable Chinese Landscape Painting Generation via Latent Diffusion Model](https://ieeexplore.ieee.org/document/10219843?denied=)
 
 **Zhongqi Wang**, Jie Zhang, Zhilong Ji, Jinfeng Bai, Shiguang Shan.
- The work is for Chinese landscape painting generation.
- Our approach outperforms the state-of-the-art methods in terms of both artfully-composed, artistic conception and Turing test.
- We built a new dataset named CLAP for text-conditional Chinese landscape generation.

</div>
</div>

# Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS (Major)</div><img src='images/TwT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trigger without Trace: Towards Stealthy Backdoor Attack on Text-to-Image Diffusion Models](https://arxiv.org/html/2503.17724v2)
 
 Jie Zhang, **Zhongqi Wang**, Shiguang Shan, Xilin Chen. (Student first author)
- It leverages dual-modal features to jointly optimize the injection, significantly improving stealthiness while maintaining high attack success rate.
- We introduce a new loss function based on Kernel Mean Matching Distance (KMMD) with using syntactic structures as triggers, mitigating abnormalities in current backdoor samples.
- It successfully evades detection in over 98% of cases on three state-of-the-art backdoor detection methods.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Techrxiv</div><img src='images/Arxiv_Survey_2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Backdoor Attacks and Defenses on Large Multimodal Models: A Survey](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176618816.64264497)
 
 **Zhongqi Wang**, Jie Zhang, Kexin Bao, Yifei Liang, Shiguang Shan, Xilin Chen.
- Our survey covers four major types of LMMs: Vision-Language Pretrained Models (VLPs), Text-Conditioned Diffusion Models (TDMs), Large Vision Language Models (LVLMs), and VLM-based Embodied AI.
- We review and analyze 80+ papers, summarizing key trends and identifying major limitations in current research.
- We highlight key trends and open problems in current research.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/AMDET_2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Assimilation Matters: Model-level Backdoor Detection in Vision-Language Pretrained Models](https://arxiv.org/abs/2512.00343)
 
 **Zhongqi Wang**, Jie Zhang, Shiguang Shan, Xilin Chen.
- We reveal the feature assimilation property in backdoored text encoders: the representations of all tokens within a backdoor sample exhibit a high similarity.
- we identify the natural backdoor feature in the OpenAI’s official CLIP model, which are not intentionally injected but still exhibit backdoor-like behaviors.
- Extensive experiments on 3,600 backdoored and benign-finetuned models with two attack paradigms and three VLP model structures show that AMDET detects backdoors with an F1 score of 89.90%.

</div>
</div>


# 🏅 Honors and Awards

- _2025_ National Scholarship for Master Students.
- _2025_ Merit Student for the University of Chinese Academy of Sciences.
- _2024_ Huawei Master Scholarship.
- _2024_ Outstanding Student Scholarship (Grade 1) for the Institute of Computing Technology.
- _2024_ Merit Student for the University of Chinese Academy of Sciences.
  
# 📖 Educations

- _2023.09 - Present_, **Institute of Computing Technology, Chinese Academy of Seiences**.
  - Consecutive MS and phD in Computer Science
  - Tutor: Professor Jie Zhang and Shiguang Shan
- _2019.09 - 2023.06_, **Beijing Institute of Computing Technology**.
  - BS in Artificial Intellgence
  - Tutor: Professor Ying Fu

# ✒️ Academic Services
Invited journal reviewer for IEEE TIFS.

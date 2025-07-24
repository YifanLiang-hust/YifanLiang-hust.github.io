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

# 👋 About me 

I am Yifan Liang, a graduate student pursuing M.S. in Intelligent Science and Technology at ![AIA](../assets/icons/aia.png){width="18" style="vertical-align:middle;"}School of Artificial Intelligence and Automation(AIA), ![HUST](../assets/icons/hust.png){width="18" style="vertical-align:middle;"}Huazhong University of Science and Technology (HUST). I graduated with honors from HUST in 2025, receiving the Outstanding Undergraduate Thesis Award and being recognized as an Honored Graduate.

My research interests focus on computer vision and machine learning, particularly in vision-language models(VLMs) and out-of-distribution(OOD) detection. I am passionate about developing robust AI systems that can handle real-world challenges and uncertainties.

I have published research at top-tier AI conferences, including a **Highlight paper** at CVPR 2025 (top 2.98%), which addresses the shortcut problem in VLMs for robust OOD detection. I was also awarded the National First Prize in the 18th "Challenge Cup" National College Student Extracurricular Academic and Technological Works Competition.

# 📖 Educations
- *2021.09 - 2025.06*, B.S. in **Artificial Intelligence** @ AIA, HUST, Wuhan, China. 
- *2025.09 - 2028.06 (expected)*, M.S. in **Intelligent Science and Technology** @ AIA, HUST, Wuhan, China. 

# 🎖 Honors and Awards
- *2024.11* National First Prize of the 18th "Challenge Cup" National College Student Extracurricular Academic and Technological Works Competition
- *2025.06* Honored Graduate of HUST
- *2025.06* Outstanding Undergraduate Thesis of HUST

# 🔥 News
- *2025.06*: &nbsp;🎉🎉 I was awarded **Honored Graduate** and **Outstanding Undergraduate Thesis** by HUST.
- *2025.03*: &nbsp;🎉🎉 One paper has been selected as a **Highlight** (top 2.98%) at CVPR 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/OES.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OpenEarthSensing: Large-Scale Fine-Grained Benchmark for Open-World Remote Sensing](https://arxiv.org/pdf/2502.20668)

Xiang Xiang<sup>1†</sup>, Zhuo Xu<sup>1</sup>, Yao Deng<sup>1</sup>, Qinhao Zhou<sup>1</sup>, **Yifan Liang**<sup>1</sup>, Ke Chen<sup>2</sup>, Qingfang Zheng<sup>2</sup>, Yaowei Wang<sup>2</sup>, Xilin Chen<sup>3</sup>, Wen Gao<sup>2</sup>

<sup>1</sup>School of Artificial Intelligence and Automation, Huazhong University of Science and Technology, Wuhan, China  
<sup>2</sup>Peng Cheng Laboratory, Shenzhen, China
<sup>3</sup>Chinese Academy of Sciences, Beijing, China
<sup>†</sup>Corresponding author

[**Paper**](https://arxiv.org/abs/2502.20668) | [**Project**](https://haiv-lab.github.io/OES/) | [**Dataset**](https://www.kaggle.com/datasets/xiangexiang/openearthsensing-oes)

- Submission to **IJCV**. This work proposes a large-scale fine-grained open-world remote-sensing datasets and benchmark **OpenEarthSensing(OES)**, which supports evaluation on multiple tasks including *Out-of-Distribution Detection*, *Class-Incremental Learning*, *Coarse-to-Fine Few-Shot Class-Incremental Learning* and *Domain-Incremental Learning*. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/OSPCoOp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming Shortcut Problem in VLM for Robust Out-of-Distribution Detection](https://openaccess.thecvf.com/content/CVPR2025/papers/Xu_Overcoming_Shortcut_Problem_in_VLM_for_Robust_Out-of-Distribution_Detection_CVPR_2025_paper.pdf)

Zhuo Xu<sup>1*</sup>, Xiang Xiang<sup>1*†</sup>, **Yifan Liang**<sup>1</sup>

<sup>1</sup>School of Artificial Intelligence and Automation, Huazhong University of Science and Technology, Wuhan, China  
<sup>*</sup>Equal contribution  
<sup>†</sup>Corresponding author

[**Paper**](https://openaccess.thecvf.com/content/CVPR2025/papers/Xu_Overcoming_Shortcut_Problem_in_VLM_for_Robust_Out-of-Distribution_Detection_CVPR_2025_paper.pdf) <strong><span class='show_paper_citations' data='Ue98P8IAAAAJ:d1gkVwhDpl0C'></span></strong> | [**Project**](https://haiv-lab.github.io/OSPCoOp.github.io/) | [**Code**](https://github.com/HAIV-Lab/OSPCoOp_Imagenet-bg) | [**Dataset**](https://www.kaggle.com/datasets/xiangexiang/imagenet-bg-ospcoop-cvpr2025)
- **Highlight Paper @ CVPR 2025**. This work addresses the shortcut problem in VLMs for robust OOD detection and propose a new OOD dataset ImageNet-Bg.
</div>
</div>

# 🚀 Projects

## OpenHAIV : A Framework Towards Practical Open-World Learning
- **Description**: This is a framework for open-world object recognition, supporting *out-of-distribution detection*, *novel class discovery*, and *incremental learning* algorithms to enable robust and flexible object recognition in unconstrained environments.
<!-- - **Tech Stack**:  -->
- **Highlights**: 
  - 🧩 **Modular Design**
    - Easy experimentation with different algorithms
    - Seamless integration of new techniques
    - Flexible deployment configurations
  - 🚀 **Scalable Architecture**
    - Large-scale dataset processing
    - Distributed training capabilities
    - Efficient memory management
    - Parallel processing optimization
  - 🔌 **Extensible Framework**
    - Plugin-based algorithm integration
    - Custom loss function support
    - Flexible evaluation metrics
    - Comprehensive logging and monitoring
  
- **Links**: [Code](https://github.com/HAIV-Lab/openhaiv) | [Doc](https://yifanliang-hust.github.io/ncdia/)

## 2025 Advanced Machine Learning Course Project: CLIP-based Few-shot OOD Detection
- **Description**: Focused on CLIP-based few-shot OOD detection, implementing various prompt learning methods including CoOp, LoCoOp, and SCT.
- **Tech Stack**: CLIP, Prompt Learning, OOD Detection
- **Highlights**: 
  - Implemented and improved three different prompt learning methods for OOD detection
  - Achieved significant improvements in AUROC and FPR95 compared to baseline on ImageNet OOD Benchmark
- **Links**: [Code](https://github.com/YifanLiang-hust/Advanced_ML_Final_Project)

## 2024 NLP Course Project: Multi-modal Image Description with MiniCPM-V
- **Description**: Implementing image description generation using MiniCPM-V model with both LoRA and full fine-tuning approaches.
- **Tech Stack**: MLLM, LoRA, Gradio
- **Highlights**: 
  - Implemented both LoRA and full fine-tuning strategies on MiniCPM-V
  - Created interactive web demo for real-time image description generation
- **Links**: [Code](https://github.com/YifanLiang-hust/NLP_Final_Project)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
- **Open to internship opportunities** in artificial intelligence research and engineering, with strong foundation in machine learning, computer vision, and programming skills (Python, PyTorch, etc.). Feel free to contact me 😊

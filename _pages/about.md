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

I am a researcher working on **unified multimodal generation** and **multimodal large language models**, with a focus on text-centric multimodal generation, autoregressive image generation, visual tokenizers, and dense text rendering.

I am currently a Remote Research Intern at **Microsoft Research, Seattle**, collaborating with **JPG Lab, Central South University** under the supervision of **Linjie Li**. Previously, I was a Research Intern at **Show Lab, National University of Singapore**, supervised by **Mike Shou Zheng**.

My recent work includes **TextAtlas5M**, a large-scale dataset for dense text image generation accepted at ICML 2026; **Residual Decoder Adapter**, an ID-preserving tokenizer adaptation method for autoregressive text rendering accepted at CVPR 2026; and **TextGround4M**, a prompt-aligned dataset for layout-aware text rendering accepted at AAAI 2026.

[Google Scholar](https://scholar.google.com/citations?user=RLVSYY0AAAAJ&hl=en) · [GitHub](https://github.com/dongxingMao) · [CV](/files/cv_dongxing_updated.pdf) · [Email](mailto:m962479949@gmail.com)

# 🔥 News
- *2026*: TextAtlas5M accepted at **ICML 2026**.
- *2026*: Residual Decoder Adapter accepted at **CVPR 2026**.
- *2026*: TextGround4M accepted at **AAAI 2026**.
- *2024*: AssistGUI and VideoLLM-online accepted at **CVPR 2024**.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/500x300.png' alt="TextAtlas5M" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TextAtlas5M: A Large-scale Dataset for Dense Text Image Generation**

**Dongxing Mao**, Alex Jinpeng Wang, Jiawei Zhang, Weiming Han, Zhuobai Dong, Linjie Li, Yiqi Lin, Zhengyuan Yang, Libo Qin, Fuwei Zhang, Lijuan Wang, Min Li

- Large-scale dataset for dense text image generation, released with 65K+ downloads.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/500x300.png' alt="Residual Decoder Adapter" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Residual Decoder Adapter: ID-Preserving Tokenizer Adaption for Autoregressive Text Rendering**

**Dongxing Mao**, Alex Jinpeng Wang, Jiahao Tang, Kevin Qinghong Lin, Linjie Li, Zhengyuan Yang, Lijuan Wang, Min Li, Jingru Tan

- ID-preserving tokenizer adaptation for improving text rendering in autoregressive models without changing the original token space.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/500x300.png' alt="TextGround4M" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TextGround4M: A Prompt-Aligned Dataset for Layout-Aware Text Rendering**

**Dongxing Mao**, Yilin Wang, Linjie Li, Zhengyuan Yang, Alex Jinpeng Wang

- Prompt-aligned dataset for layout-aware text rendering.
</div>
</div>

- **ORPRM: A Process Reward Model for Algorithmic Problem in Operations Research**. Yilin Wang, Heng Zhou, **Dongxing Mao**, Linjie Li, Jingru Tan, Haochen Han, Zhengyuan Yang, Alex Jinpeng Wang, Min Li. **ICLR 2026**.
- **Efficient Frame Selection for Long Videos at Test Time with Early Layer Attention**. Yilin Wang, Xiangxi Zheng, **Dongxing Mao**, Linjie Li, Ping Yu, Rui Yan, Yuan Yao, Zhengyuan Yang, Lijuan Wang, Alex Jinpeng Wang. Submitted to **ECCV 2026**.
- **VidCode: Benchmarking Multimodal Code Generation for Video Animation**. Yuhao Zheng, Hangyu Ran, **Dongxing Mao**, Linjie Li, Puzhen Zhang, Guohao Li, Linyuan Lü, Philip Torr, Alex Jinpeng Wang, Kevin Qinghong Lin. Submitted to **ECCV 2026**.
- **DuetGen: Bridging Autoregressive and Diffusion Models for Text Render Image Generation**. Guanqiao Chen, Jingru Tan, **Dongxing Mao**, Libo Qin, Hu Jian Guo, Alex Jinpeng Wang. Submitted to **ECCV 2026**.
- **VCode: A Multimodal Coding Benchmark with SVG as Symbolic Visual Representation**. Kevin Qinghong Lin, Yuhao Zheng, Hangyu Ran, **Dongxing Mao**, Dantong Zhu, Linjie Li, Philip Torr, Alex Jinpeng Wang. Preprint.
- **AssistGUI: Task-oriented Desktop Graphical User Interface Automation**. Difei Gao, Lei Ji, Zechen Bai, Mingyu Ouyang, Peiran Li, **Dongxing Mao**, Qinchen Wu, Weichen Zhang, Peiyi Wang, Xiangwu Guo, Hengxu Wang, Luowei Zhou, Mike Zheng Shou. **CVPR 2024**.
- **VideoLLM-online: Towards Large Video Language Model for Streaming Video**. Joya Chen, Zhaoyang Lv, Shiwei Wu, Kevin Qinghong Lin, Chenan Song, Difei Gao, JiaWei Liu, Ziteng Gao, **Dongxing Mao**, Mike Zheng Shou. **CVPR 2024**.
- **AssistSR: Task-oriented Video Segment Retrieval for Personal AI Assistant**. Stan Weixian Lei, Yuxuan Wang, **Dongxing Mao**, Difei Gao, Mike Zheng Shou. **EMNLP 2022**.
- **AssistQ: Affordance-centric Question-driven Task Completion for Egocentric Assistant**. Benita Wong, Joya Chen, You Wu, Stan Weixian Lei, **Dongxing Mao**, Difei Gao, Mike Zheng Shou. **ECCV 2022**.

# 💻 Research Experience

- *2024.10 - Present*, **Remote Research Intern**, Microsoft Research, Seattle.  
  Collaborative research with JPG Lab, Central South University. Supervisor: Linjie Li.
  - Conduct research on text-centric multimodal generation, focusing on autoregressive image generation, visual tokenizers, and dense text rendering.
  - Proposed Residual Decoder Adapter (RDA), an ID-preserving tokenizer adaptation method accepted at CVPR 2026.
  - Led the construction of TextAtlas5M and TextGround4M, accepted at ICML 2026 and AAAI 2026.
  - Built large-scale data processing, training, and evaluation pipelines for multimodal generation, including OCR-based evaluation, layout-aware metrics, and distributed training.

- *2021.08 - 2024.09*, **Research Intern**, Show Lab, National University of Singapore.  
  Supervisor: Mike Shou Zheng.
  - Conducted research on multimodal understanding and video-language models, with a focus on streaming, interactive, and assistant-oriented scenarios.
  - Contributed to systems and benchmarks including AssistGUI, VideoLLM-online, AssistSR, and AssistQ.
  - Worked on GUI automation, streaming video understanding, task-oriented video retrieval, and egocentric assistant reasoning.

# 📖 Education

- *2021.08 - 2023.01*, **National University of Singapore**, M.Sc. in Electrical and Computer Engineering. GPA: 4.25/5.00.
- *2017.09 - 2021.06*, **Nanjing University of Science and Technology**, B.Eng. in Telecommunications Engineering. GPA: 88.3/100.
- *2019.06 - 2019.08*, **University of California, Los Angeles**, Summer Exchange Student.

# 🎖 Service

- Reviewer: ECCV, AAAI, ICLR, CVPR.
- Organizer: CVPR 2023 Workshop LOVEU.

# 🧰 Skills

- **Research expertise:** Generative AI, diffusion models, autoregressive models, multimodal understanding.
- **Deep learning frameworks:** PyTorch, HuggingFace Diffusers, Transformers, Accelerate, DeepSpeed.
- **Large-scale computing:** distributed training, Linux, WandB, TensorBoard.
- **Programming/tools:** Python, C++, MATLAB, LaTeX, Git.
- **Languages:** Mandarin Chinese native, English IELTS 7.

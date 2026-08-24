---
permalink: /
title: ""
excerpt: "Systems researcher working on efficient LLM inference, agent systems, and computer architecture."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I'm Zhuohang Bian, an incoming Ph.D. student at the [School of Integrated Circuits](https://ic.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/). Before that, I studied Computer Science and Technology at [Beihang University](https://www.buaa.edu.cn/), where I ranked in the top 10% of my major (19/239) with a GPA of 3.86/4.

My research interests center on efficient LLM inference systems, multi-agent workloads, computer architecture, and hardware-software co-design. I am currently working with Prof. Youwei Zhuo on agent systems. If you are interested in potential collaborations or would like to discuss anything, please feel free to reach out by email. Here is my [CV](https://zhhangbian.github.io/CV/cv_en.pdf).

## News

- *2026.08*: **TokenCake** was accepted to **EuroSys 2027**.
- *2026.04*: We released **TokenDance**, a system for collective KV cache sharing in multi-agent LLM serving.
- *2025.10*: I completed a systems internship at SenseTime, with six pull requests merged into [LightLLM](https://github.com/ModelTC/LightLLM).
- *2025*: Our large-scale study on robust cooperative multi-agent reinforcement learning appeared at **NeurIPS 2025**.
- *2024*: Our MT-3000 attention optimization received an **Outstanding Paper** award at HPC China 2024.

## Selected Publications

- **TokenCake: A KV-Cache-centric Serving Framework for LLM-based Multi-Agent Applications**\\
  **<u>Zhuohang Bian</u>**, Feiyang Wu, Zhuoran Li, Teng Ma, Youwei Zhuo\\
  **_EuroSys 2027_**\\
  [[paper](https://arxiv.org/pdf/2510.18586)]

- **TokenDance: Scaling Multi-Agent LLM Serving via Collective KV Cache Sharing**\\
  **<u>Zhuohang Bian</u>**, Feiyang Wu, Chengrui Zhang, Hangcheng Dong, Yun Liang, Youwei Zhuo\\
  **_Preprint_**\\
  [[paper](https://arxiv.org/pdf/2604.03143)]

- **TokenSim: Enabling Hardware and Software Exploration for Large Language Model Inference Systems**\\
  Feiyang Wu, **<u>Zhuohang Bian</u>**, Guoyang Duan, Tianle Xu, Junchi Wu, Teng Ma, Yongqiang Yao, Ruihao Gong, Youwei Zhuo\\
  **_Preprint_**\\
  [[paper](https://arxiv.org/pdf/2503.08415)]

- **Empirical Study on Robustness and Resilience in Cooperative Multi-Agent Reinforcement Learning**\\
  Simin Li, Zihao Mao, Hanxiao Li, Zonglei Jing, **<u>Zhuohang Bian</u>**, Jun Guo, Li Wang, Zhuoran Han, Ruixiao Xu, Xin Yu, Chengdong Ma, Yuqing Ma, Bo An, Yaodong Yang, Weifeng Lv, Xianglong Liu\\
  **_NeurIPS 2025_**\\
  [[paper](https://arxiv.org/pdf/2510.11824)] [[code](https://github.com/BUAA-TrustworthyMARL/adv_marl_benchmark)]

## Research Experience

- **Peking University, School of Integrated Circuits**\\
  *Research Assistant, Prof. Youwei Zhuo's Group, Feb 2025 - Present*\\
  I lead research on KV-cache-centric serving for multi-agent LLM applications. TokenCake combines agent-aware scheduling and memory management, while TokenDance introduces collective KV cache sharing and block-sparse diff storage.

- **State Key Laboratory of Complex & Critical Software Environment, Beihang University**\\
  *Research Assistant, Prof. Xianglong Liu's Group, Jul 2024 - Jan 2025*\\
  I built AMB, a robustness benchmark covering four real-world environments, 13 uncertainty types, 15 key hyperparameters, and 82,620 experiments for cooperative multi-agent reinforcement learning.

- **Sino-German Joint Software Institute, Beihang University**\\
  *Research Assistant, Prof. Zhongzhi Luan's Group, Sep 2023 - May 2024*\\
  I optimized multi-head attention for the MT-3000 CPU-DSP heterogeneous processor with matrix tiling, DMA double buffering, communication optimization, and head-level operator scheduling.

## Industry Experience

- **SenseTime - LightLLM**\\
  *Systems Research Intern, Jun 2025 - Oct 2025*\\
  I worked on prefill-decode disaggregated scheduling, memory-aware routing, cross-GPU KV cache migration, and MinerU2 multimodal model support. Six public pull requests were merged: [#944](https://github.com/ModelTC/LightLLM/pull/944), [#970](https://github.com/ModelTC/LightLLM/pull/970), [#999](https://github.com/ModelTC/LightLLM/pull/999), [#1011](https://github.com/ModelTC/LightLLM/pull/1011), [#1024](https://github.com/ModelTC/LightLLM/pull/1024), and [#1034](https://github.com/ModelTC/LightLLM/pull/1034).

## Selected Projects

- **Out-of-order LoongArch Processor**\\
  I implemented key backend modules for a 13-stage dual-issue superscalar processor supporting LoongArch32R. The processor boots Linux, reached 80 MHz on FPGA, and placed fourth nationally in the 2024 Loongson Cup CPU Track. [[code](https://github.com/zhhangBian/BOOM_chip)]

- **Compiler Course Infrastructure**\\
  I developed a compiler course project that was adopted as a teaching example in national compiler-course teacher training. [[code](https://github.com/zhhangBian/Compiler-Techniques)]

## Honors and Awards

- **First Prize**, China Undergraduate Mathematical Contest in Modeling
- **4th Place / Second Prize**, Loongson Cup CPU Track
- **First Prize**, Physics Competition
- **AVIC Scholarship**
- **BUAA Academic Excellence Scholarship, First Prize**
- **Competition Scholarship, Top Prize**
- **Innovation and Entrepreneurship Scholarship, Second Prize**

## Education

- *2026 - (incoming)*, Ph.D. Student, Electronic Design Automation and Computing Systems, School of Integrated Circuits, Peking University
- *2022 - 2026*, B.Eng. in Computer Science and Technology, School of Computer Science and Engineering, Beihang University

## Teaching

- Advanced Teaching Assistant, Computer Organization, Beihang University
- Teaching Assistant, Operating Systems, Beihang University

## Skills

- **Programming:** Python, C++, CUDA, SystemVerilog
- **Systems:** LLM serving, distributed inference, processor design, reinforcement-learning experiment platforms
- **English:** CET-6, 589

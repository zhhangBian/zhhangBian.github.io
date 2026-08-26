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

I'm Zhuohang Bian (卞卓航), a Ph.D. student at the [School of Integrated Circuits](https://ic.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/). Before that, I studied Computer Science and Technology at [Beihang University](https://www.buaa.edu.cn/).

My research interests center on efficient LLM inference systems, multi-agent workloads, computer architecture, and hardware-software co-design. I am currently working with Prof. Youwei Zhuo on agent systems. If you are interested in potential collaborations or would like to discuss anything, please feel free to reach out by email. Here is my [CV](https://zhhangbian.github.io/CV/cv_en.pdf).

# 🔥 News {#news}

- *2026.08*: 🎉 **TokenCake** was accepted to **EuroSys 2027**.
- *2026.08*: 🎤 I am serving as the chair of the APPT tutorial **T2: Graph.hls: A Compiler Framework for Composable Graph Accelerator Design**.
- *2026.07*: 🎉 **TokenSimV2: Accurate and Fast Modeling for LLM Inference on GPUs** was accepted to **APPT**.
- *2026.06*: 🏆 I was awarded the title of **Outstanding Graduate of Beijing** (北京市优秀毕业生).
- *2026.04*: 🚀 We released [**TokenDance**](https://arxiv.org/pdf/2604.03143), a system for collective KV cache sharing in multi-agent LLM serving.
- *2025.10*: 💻 I completed a systems internship at SenseTime, with six pull requests merged into [LightLLM](https://github.com/ModelTC/LightLLM).
- *2025.09*: 🎓 I was admitted to the Ph.D. program at the School of Integrated Circuits, Peking University.

# 🎓 Education {#education}

- <span class="timeline-date">2026 - Present</span>, **Peking University**, School of Integrated Circuits <span class="timeline-role">Ph.D. Student in Electronic Design Automation and Computing Systems</span>
- <span class="timeline-date">2022 - 2026</span>, **Beihang University**, School of Computer Science and Engineering <span class="timeline-role">B.Eng. in Computer Science and Technology</span>
{: .timeline-list }

# 💼 Experiences {#experiences}

- <span class="timeline-date">Feb 2025 - Present</span>, **Peking University, School of Integrated Circuits** <span class="timeline-role">Research Assistant</span>\\
  <span class="timeline-description">Working with [Prof. Youwei Zhuo's Group](https://www.youwei.xyz/), I lead research on KV-cache-centric serving for multi-agent LLM applications. TokenCake combines agent-aware scheduling and memory management, while TokenDance introduces collective KV cache sharing and block-sparse diff storage.</span>

- <span class="timeline-date">Jun 2025 - Oct 2025</span>, **SenseTime - LightLLM** <span class="timeline-role">Systems Research Intern</span>\\
  <span class="timeline-description">I worked on prefill-decode disaggregated scheduling, memory-aware routing, cross-GPU KV cache migration, and MinerU2 multimodal model support. Six public pull requests were merged: [#944](https://github.com/ModelTC/LightLLM/pull/944), [#970](https://github.com/ModelTC/LightLLM/pull/970), [#999](https://github.com/ModelTC/LightLLM/pull/999), [#1011](https://github.com/ModelTC/LightLLM/pull/1011), [#1024](https://github.com/ModelTC/LightLLM/pull/1024), and [#1034](https://github.com/ModelTC/LightLLM/pull/1034).</span>

- <span class="timeline-date">Jul 2024 - Jan 2025</span>, **State Key Laboratory of Complex & Critical Software Environment, Beihang University** <span class="timeline-role">Research Assistant</span>\\
  <span class="timeline-description">Working with Prof. Xianglong Liu's Group, I built AMB, a robustness benchmark covering four real-world environments, 13 uncertainty types, 15 key hyperparameters, and 82,620 experiments for cooperative multi-agent reinforcement learning.</span>

- <span class="timeline-date">Sep 2023 - May 2024</span>, **Sino-German Joint Software Institute, Beihang University** <span class="timeline-role">Research Assistant</span>\\
  <span class="timeline-description">Working with Prof. Zhongzhi Luan's Group, I optimized multi-head attention for the MT-3000 CPU-DSP heterogeneous processor with matrix tiling, DMA double buffering, communication optimization, and head-level operator scheduling.</span>
{: .timeline-list }

# 📝 Publications {#selected-publications}

- <span class="venue-badge venue-badge--published">EuroSys 2027</span> **TokenCake: A KV-Cache-centric Serving Framework for LLM-based Multi-Agent Applications**\\
  **<u>Zhuohang Bian</u>**, Feiyang Wu, Zhuoran Li, Teng Ma, Youwei Zhuo\\
  [[paper](https://arxiv.org/pdf/2510.18586)]

- <span class="venue-badge venue-badge--preprint">Preprint</span> **TokenDance: Scaling Multi-Agent LLM Serving via Collective KV Cache Sharing**\\
  **<u>Zhuohang Bian</u>**, Feiyang Wu, Chengrui Zhang, Hangcheng Dong, Yun Liang, Youwei Zhuo\\
  [[paper](https://arxiv.org/pdf/2604.03143)]

- <span class="venue-badge venue-badge--preprint">Preprint</span> **A Full-Stack Characterization of High-Bandwidth Flash for KV-Centric LLM Serving**\\
  Zhuoran Li, **<u>Zhuohang Bian</u>**, Xin Huang, Yibo Zhao, Guangyu Sun, Youwei Zhuo\\
  [[paper](https://arxiv.org/pdf/2608.11668)]

- <span class="venue-badge venue-badge--preprint">Preprint</span> **TokenStack: A Heterogeneous HBM-PIM Architecture and Runtime for Efficient LLM Inference**\\
  Zhuoran Li, **<u>Zhuohang Bian</u>**, Zihao Huang, Yibo Zhao, Xueqi Li, Guangyu Sun, Youwei Zhuo\\
  [[paper](https://arxiv.org/pdf/2605.05639)]

- <span class="venue-badge venue-badge--published">ISCA 2026</span> **Graph.hls: A Compiler Framework for Composable Graph Accelerator Design**\\
  Feiyang Wu, Xuxiao Yang, **<u>Zhuohang Bian</u>**, Jing Wang, Ruifan Xu, Guangyu Sun, Yun Liang, Youwei Zhuo\\
  [[paper](https://doi.org/10.1109/ISCA66397.2026.00064)]

- <span class="venue-badge venue-badge--published">APPT 2025</span> **TokenSim: Enabling Hardware and Software Exploration for Large Language Model Inference Systems**\\
  Feiyang Wu, **<u>Zhuohang Bian</u>**, Guoyang Duan, Tianle Xu, Junchi Wu, Teng Ma, Yongqiang Yao, Ruihao Gong, Youwei Zhuo\\
  [[paper](https://arxiv.org/pdf/2503.08415)]

- <span class="venue-badge venue-badge--published">KDD 2026</span> **MammoExpert: Benchmarking Chain-of-Thought Reasoning in Mammography Diagnosis**\\
  Di Dai, Bo Liu, Youcheng Li, Haojun Yu, **<u>Zhuohang Bian</u>**, Quanlin Wu, Dong Wang, Sichen Meng, Hongye Xuan, Zijie Lan, Shenda Hong, Liwei Wang\\
  [[paper](https://arxiv.org/pdf/2606.21119)]

- <span class="venue-badge venue-badge--published">NeurIPS 2025</span> **Empirical Study on Robustness and Resilience in Cooperative Multi-Agent Reinforcement Learning**\\
  Simin Li, Zihao Mao, Hanxiao Li, Zonglei Jing, **<u>Zhuohang Bian</u>**, Jun Guo, Li Wang, Zhuoran Han, Ruixiao Xu, Xin Yu, Chengdong Ma, Yuqing Ma, Bo An, Yaodong Yang, Weifeng Lv, Xianglong Liu\\
  [[paper](https://arxiv.org/pdf/2510.11824)] [[code](https://github.com/BUAA-TrustworthyMARL/adv_marl_benchmark)]

# 🛠️ Projects {#selected-projects}

- **Out-of-order LoongArch Processor**\\
  I implemented key backend modules for a 13-stage dual-issue superscalar processor supporting LoongArch32R. The processor boots Linux, reached 80 MHz on FPGA, and placed fourth nationally in the 2024 Loongson Cup CPU Track. [[code](https://github.com/zhhangBian/BOOM_chip)]

- **Compiler Course Infrastructure**\\
  I developed a compiler course project that was adopted as a teaching example in national compiler-course teacher training. [[code](https://github.com/zhhangBian/Compiler-Techniques)]

# 🏅 Awards {#honors-and-awards}

- **Outstanding Graduate of Beijing** — Beijing Municipal Education Commission, 2026
- **First Prize, China Undergraduate Mathematical Contest in Modeling** — National Level, China Society for Industrial and Applied Mathematics, Nov 2024 (Team Award)
- **4th Place / Second Prize, Loongson Cup CPU Track** — National College Student Computer System Ability Competition, Aug 2024 (Team Award)
- **First Prize (Meritorious Winner), International Mathematical Contest in Modeling** — The Consortium for Mathematics and its Applications, May 2024 (Team Award)
- **Second Prize, National College Student Computer System Ability Competition** — National Association of Computer Education in Colleges and Universities, Aug 2025 (Team Award)
- **First Prize, Physics Competition** — Beijing Physical Society, Dec 2023
- **AVIC Scholarship** — Aviation Industry Corporation of China
- **BUAA Academic Excellence Scholarship, First Prize** — Beihang University
- **Competition Scholarship, Top Prize** — Beihang University
- **Innovation and Entrepreneurship Scholarship, Second Prize** — Beihang University
- **Outstanding Student Leader of Beihang University** (2023, 2024, 2025)
- **Outstanding League Cadre of Beihang University** 
- **Outstanding Student of Beihang University**

# 🤝 Service {#service}

- **Tutorial Chair**, APPT\\
  *T2: Graph.hls: A Compiler Framework for Composable Graph Accelerator Design*

# 👨‍🏫 Teaching {#teaching}

- Advanced Teaching Assistant, Computer Organization, Beihang University, 2025/1-2025/12
- Teaching Assistant, Operating Systems, Beihang University, 2024/09-2025/06
- Teaching Assistant, Computer Organization, Beihang University, 2024/07-2024/12

{% comment %}
# 🧰 Skills {#skills}

- **Programming:** Python, C++, CUDA, SystemVerilog
- **Systems:** LLM serving, distributed inference, processor design, reinforcement-learning experiment platforms
- **English:** CET-6
{% endcomment %}

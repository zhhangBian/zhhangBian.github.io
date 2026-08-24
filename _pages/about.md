---
permalink: /
title: ""
excerpt: "Systems researcher working on efficient LLM inference, agent systems, and computer architecture."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="profile-intro" id="about-me">
  <div class="profile-intro__copy">
    <h1>Zhuohang Bian</h1>
    <p class="profile-intro__lead">I build efficient systems for LLM inference and agent workloads, with a broader interest in computer architecture and hardware-software co-design.</p>
    <p class="profile-intro__affiliation">I am completing my B.Eng. in Computer Science at Beihang University and will join Peking University's School of Integrated Circuits as a Ph.D. student in 2026.</p>
    <div class="profile-actions" aria-label="Profile links">
      <a class="profile-action profile-action--primary" href="mailto:bianzhuohang26@stu.pku.edu.cn"><i class="fas fa-envelope" aria-hidden="true"></i>Email</a>
      <a class="profile-action" href="https://zhhangbian.github.io/CV/cv_en.pdf"><i class="fas fa-file-alt" aria-hidden="true"></i>CV</a>
      <a class="profile-action" href="https://github.com/zhhangBian"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    </div>
  </div>
  <figure class="profile-intro__portrait">
    <img src="/images/headshot.jpg" alt="Portrait of Zhuohang Bian">
    <figcaption>Beijing, China</figcaption>
  </figure>
</section>

<section class="content-section news-section" id="news">
  <header class="section-heading">
    <h2>News</h2>
    <p>Recent research and engineering updates.</p>
  </header>
  <div class="news-list">
    <div class="news-item"><time datetime="2026-08">Aug 2026</time><p><strong>TokenCake</strong> was accepted to <strong>EuroSys 2027</strong>.</p></div>
    <div class="news-item"><time datetime="2025-10">Oct 2025</time><p>Completed a systems internship at SenseTime, contributing six merged pull requests to <a href="https://github.com/ModelTC/LightLLM">LightLLM</a>.</p></div>
    <div class="news-item"><time datetime="2025">2025</time><p>Our work on robust multi-agent reinforcement learning appeared at <strong>NeurIPS 2025</strong>.</p></div>
    <div class="news-item"><time datetime="2024">2024</time><p>Received an Outstanding Paper award at <strong>HPC China 2024</strong> for MT-3000 attention optimization.</p></div>
  </div>
</section>

<section class="content-section" id="publications">
  <header class="section-heading">
    <h2>Publications</h2>
    <p>Selected work in LLM serving, agent systems, and efficient computing.</p>
  </header>
  <div class="publication-list">
    <article class="publication-item publication-item--featured">
      <div class="publication-venue">EuroSys 2027</div>
      <div class="publication-copy">
        <h3><a href="https://arxiv.org/abs/2510.18586">TokenCake: A KV-Cache-centric Serving Framework for LLM-based Multi-Agent Applications</a></h3>
        <p class="publication-meta"><strong>First author.</strong> Accepted to EuroSys 2027.</p>
        <p>Introduces agent-aware time and space scheduling with proactive offload, predictive upload, and dynamic memory partitioning. TokenCake reduces end-to-end latency by 47.06% over vLLM and improves effective GPU KV cache utilization by 16.9%.</p>
        <a class="text-link" href="https://arxiv.org/abs/2510.18586">arXiv <i class="fas fa-arrow-right" aria-hidden="true"></i></a>
      </div>
    </article>

    <article class="publication-item">
      <div class="publication-venue">Preprint</div>
      <div class="publication-copy">
        <h3><a href="https://arxiv.org/abs/2604.03143">TokenDance: Scaling Multi-Agent LLM Serving via Collective KV Cache Sharing</a></h3>
        <p class="publication-meta"><strong>First author.</strong></p>
        <p>Round-level collective KV reuse and block-sparse diff storage for multi-agent LLM serving, supporting 2.7x more concurrent agents than vLLM with prefix caching and improving prefill throughput by 1.9x.</p>
        <a class="text-link" href="https://arxiv.org/abs/2604.03143">arXiv <i class="fas fa-arrow-right" aria-hidden="true"></i></a>
      </div>
    </article>

    <article class="publication-item">
      <div class="publication-venue">Preprint</div>
      <div class="publication-copy">
        <h3><a href="https://arxiv.org/abs/2503.08415">TokenSim: Enabling Hardware and Software Exploration for Large Language Model Inference Systems</a></h3>
        <p class="publication-meta"><strong>Second author.</strong></p>
        <p>A software and hardware co-simulator for dynamic LLM serving, including scheduler and memory-manager simulation and prefill-decode disaggregation exploration, with below 1% error on real workloads.</p>
        <a class="text-link" href="https://arxiv.org/abs/2503.08415">arXiv <i class="fas fa-arrow-right" aria-hidden="true"></i></a>
      </div>
    </article>

    <article class="publication-item">
      <div class="publication-venue">NeurIPS 2025</div>
      <div class="publication-copy">
        <h3><a href="https://arxiv.org/abs/2510.11824">Empirical Study on Robustness and Resilience in Cooperative Multi-Agent Reinforcement Learning</a></h3>
        <p>Evaluates 13 uncertainty types and 15 key hyperparameters across four real-world environments, backed by 82,620 experiments.</p>
        <a class="text-link" href="https://arxiv.org/abs/2510.11824">arXiv <i class="fas fa-arrow-right" aria-hidden="true"></i></a>
      </div>
    </article>
  </div>
</section>

<section class="content-section" id="experience">
  <header class="section-heading">
    <h2>Experience</h2>
    <p>Research groups and selected systems engineering.</p>
  </header>
  <div class="experience-list">
    <article class="experience-item">
      <div class="experience-date">2025 - Present</div>
      <div>
        <h3>Peking University, School of Integrated Circuits</h3>
        <p class="experience-role">Research Assistant · Prof. Youwei Zhuo's Group</p>
        <p>Researching agent systems and efficient LLM serving. Led TokenCake and TokenDance and contributed to the TokenSim inference simulator.</p>
      </div>
    </article>
    <article class="experience-item">
      <div class="experience-date">2025</div>
      <div>
        <h3>SenseTime · LightLLM</h3>
        <p class="experience-role">Systems Research Intern</p>
        <p>Worked on prefill-decode disaggregated scheduling, memory-aware routing, cross-GPU KV cache migration, and multimodal model support. Six public pull requests were merged.</p>
      </div>
    </article>
    <article class="experience-item">
      <div class="experience-date">2024 - 2025</div>
      <div>
        <h3>State Key Laboratory of Complex &amp; Critical Software Environment</h3>
        <p class="experience-role">Research Assistant · Prof. Xianglong Liu's Group</p>
        <p>Built AMB, a large-scale robustness benchmark for multi-agent reinforcement learning, and contributed experiment infrastructure and analysis.</p>
      </div>
    </article>
    <article class="experience-item">
      <div class="experience-date">2023 - 2024</div>
      <div>
        <h3>Sino-German Joint Software Institute, Beihang University</h3>
        <p class="experience-role">Research Assistant · Prof. Zhongzhi Luan's Group</p>
        <p>Optimized multi-head attention on the MT-3000 CPU-DSP heterogeneous processor using tiling, DMA double buffering, communication optimization, and operator scheduling.</p>
      </div>
    </article>
  </div>

  <div class="selected-work">
    <article>
      <h3><a href="https://github.com/zhhangBian/BOOM_chip">Out-of-order LoongArch processor</a></h3>
      <p>Implemented backend modules for a 13-stage dual-issue superscalar processor that boots Linux and reached fourth place nationally in the 2024 Loongson Cup CPU Track.</p>
    </article>
    <article>
      <h3><a href="https://github.com/zhhangBian/Compiler-Techniques">Teaching and course infrastructure</a></h3>
      <p>Advanced teaching assistant for Computer Organization and teaching assistant for Operating Systems. A compiler course project was adopted for national teacher training.</p>
    </article>
  </div>
</section>

<section class="content-section education-section" id="education">
  <header class="section-heading">
    <h2>Education</h2>
    <p>Academic training and selected honors.</p>
  </header>
  <div class="education-list">
    <article class="education-item">
      <div class="education-mark">PKU</div>
      <div><h3>Peking University</h3><p>Incoming Ph.D., Electronic Design Automation and Computing Systems</p></div>
      <time>2026 -</time>
    </article>
    <article class="education-item">
      <div class="education-mark">BUAA</div>
      <div><h3>Beihang University</h3><p>B.Eng., Computer Science and Technology · GPA 3.86/4 · Top 10%</p></div>
      <time>2022 - 2026</time>
    </article>
  </div>
  <div class="honors-line">
    <h3>Selected honors</h3>
    <p>First Prize, China Undergraduate Mathematical Contest in Modeling · AVIC Scholarship · BUAA Academic Excellence Scholarship, First Prize · 4th Place, Loongson Cup CPU Track</p>
  </div>
</section>

<footer class="site-signoff">
  <p>© 2026 Zhuohang Bian</p>
  <div><a href="mailto:bianzhuohang26@stu.pku.edu.cn">Email</a><a href="https://github.com/zhhangBian">GitHub</a><a href="https://zhhangbian.github.io/CV/cv.pdf">中文简历</a></div>
</footer>

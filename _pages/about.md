---
permalink: /
title: ""
description: "Yunhao Hou, M.Sc. student at USTB. Research in embodied AI, vision-language-action models, robot learning, and aerial-ground collaboration."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am a master's student in Computer Science and Technology at the [University of Science and Technology Beijing (USTB)](https://www.ustb.edu.cn/), advised by [Prof. Huimin Ma](https://scce.ustb.edu.cn/info/1013/1010.htm). I received my bachelor's degree from USTB in 2024 and expect to graduate with my master's degree in June 2027.

My research focuses on **embodied AI**, with an emphasis on vision-language-action models for dexterous manipulation and navigation. I am also interested in **embodied reasoning and planning**: building agents that connect task decomposition, memory, and skill orchestration to physical action, as well as aerial-ground collaboration for autonomous driving.

<div class="tag-row">
  <span class="tag">Embodied AI</span>
  <span class="tag">Vision-Language-Action Models</span>
  <span class="tag">Dexterous Manipulation</span>
  <span class="tag">Aerial-Ground Collaboration</span>
  <span class="tag">Embodied Reasoning &amp; Planning</span>
</div>

I am currently an embodied AI algorithm intern at **AgiBot**. Previously, I interned at **JD Future Academy** and **LinkerBot**, working on robot navigation, dexterous manipulation, and multimodal policies. I led **AGC-Drive**, a real-world aerial-ground collaborative perception dataset published at **NeurIPS 2025**.

<div class="notice notice--info" markdown="1">
I am seeking full-time algorithm roles in embodied AI and robotics through the 2027 graduate recruitment cycle, with an expected graduation date of June 2027. My interests include VLA models, embodied agents, and agentic reinforcement learning. Feel free to contact me at [16601210597@163.com](mailto:16601210597@163.com).
</div>

## News
{: #news }

- **2026.06** — Joined AgiBot as an embodied AI algorithm intern.
- **2026.03** — Joined JD Future Academy to work on embodied navigation.
- **2025** — Our first-author paper **AGC-Drive** was published at **NeurIPS 2025**, Datasets and Benchmarks Track.

## Publications
{: #publications }

<div class="paper-box">
  <div class="paper-box-image"><div><img src="{{ '/images/agc-drive.png' | relative_url }}" alt="AGC-Drive data collection platform with two vehicles and a UAV" loading="lazy"></div></div>
  <div class="paper-box-text" markdown="1">

<div class="publication-meta"><span class="venue-badge">NeurIPS 2025</span><span class="venue-track">Datasets and Benchmarks Track</span></div>

**AGC-Drive: A Large-Scale Dataset for Real-World Aerial-Ground Collaboration in Driving Scenarios**

**Yunhao Hou**, Bochao Zou, Min Zhang, Ran Chen, Shangdong Yang, Yanmei Zhang, Junbao Zhuo, Siheng Chen, Jiansheng Chen, Huimin Ma

A real-world collaborative perception dataset with 350 scenes, 14 driving scenarios, 13 object categories, and over 720K annotated 3D bounding boxes.

[**Paper**]({{ '/assets/file/agc-drive-neurips-2025.pdf' | relative_url }}) · [**Code & Dataset**](https://github.com/AGC-Drive/AGC-Drive)

  </div>
</div>

### Manuscripts under review

<div class="paper-box paper-box--manuscript">
  <div class="paper-box-text" markdown="1">

<div class="publication-meta"><span class="venue-badge venue-badge--review">IEEE TPAMI · Under review</span></div>

**AGC-Drive-VLA: A Vision-Language-Action Dataset and Benchmark for Bridging the Perception-Decision Gap in Aerial-Ground Collaboration**

First author

Extending aerial-ground collaboration from perception to language-conditioned decision-making through collaborative scene descriptions, question answering, and a VLA evaluation benchmark.

  </div>
</div>

<div class="paper-box paper-box--manuscript">
  <div class="paper-box-text" markdown="1">

<div class="publication-meta"><span class="venue-badge venue-badge--review">AAAI · Under review</span></div>

**AestheticVLM: From Aesthetic Preferences to Continuous Control of Image Generation**

Co-first author

Aligning vision-language models with human aesthetic preferences through multimodal reward modeling, supervised fine-tuning, and GRPO, and guiding diffusion-based generation with aesthetic scores.

  </div>
</div>

<div class="paper-box paper-box--manuscript">
  <div class="paper-box-text" markdown="1">

<div class="publication-meta"><span class="venue-badge venue-badge--review">AAAI · Under review</span></div>

**CW2S-InfAlign: Contrastive Guidance for Weak-to-Strong Inference-Time Alignment of Large Language Models**

Second author

An inference-time alignment framework using contrastive guidance from weak experts and synergistic token-level and chunk-level interventions.

  </div>
</div>

<div class="paper-box paper-box--manuscript">
  <div class="paper-box-text" markdown="1">

<div class="publication-meta"><span class="venue-badge venue-badge--review">AAAI · Under review</span></div>

**Geo-VLA: Geometry-Aware Vision-Language-Action Planning via Internalization of Map Semantics**

Third author

Learning geometry-aware visual representations from map semantics during training, with no HD maps or additional lane information required at inference time.

  </div>
</div>

## Research Projects
{: #projects }

<div class="info-card">
  <div class="card-icon"><img src="{{ '/images/lab-mark.png' | relative_url }}" alt="3D Image Lab" loading="lazy"></div>
  <div class="card-body">
    <div class="card-title">Aerial-Ground Collaboration and VLA Decision Benchmark<span class="card-role">Project Lead</span></div>
    <div class="card-sub">Completed ahead of schedule · All project tasks completed and project closed in early 2026</div>
    <div class="card-note">Built a real-world system with two vehicles and a UAV, synchronized LiDAR, camera, and IMU data, and developed a large-scale collaborative perception dataset. Extended the work toward language-conditioned scene understanding and decision-making. Related work, Geo-VLA, learns road geometry and topology within VLA representations to reduce reliance on HD maps at inference time.</div>
  </div>
  <div class="card-date">Nov. 2023 – Early 2026</div>
  <div class="icon-chip ended" title="Completed" aria-label="Completed"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg></div>
</div>

<div class="info-card">
  <div class="card-icon"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M19.8 18.4L14 10.67V6.5l1.35-1.69c.26-.33.03-.81-.39-.81H9.04c-.42 0-.65.48-.39.81L10 6.5v4.17L4.2 18.4c-.49.66-.02 1.6.8 1.6h14c.82 0 1.29-.94.8-1.6z"/></svg></div>
  <div class="card-body">
    <div class="card-title">AestheticVLM: Vision-Language Model Preference Alignment<span class="card-role">Project Lead</span></div>
    <div class="card-sub">Multimodal reward modeling and generation · Completed in July 2026</div>
    <div class="card-note">Built a multimodal preference dataset and reward model, then combined supervised fine-tuning and GRPO to align vision-language generation with human aesthetic preferences. Used compact aesthetic scores to guide diffusion-based image generation.</div>
  </div>
  <div class="card-date">Jan. – Jul. 2026</div>
  <div class="icon-chip ended" title="Completed" aria-label="Completed"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg></div>
</div>

## Internships
{: #internships }

<div class="info-card"><div class="company-logo"><img src="{{ '/images/agibot.png' | relative_url }}" alt="AgiBot logo" loading="lazy"></div><div class="card-body"><div class="card-title">AgiBot · 智元机器人</div><div class="card-sub">Embodied AI Algorithm Intern</div><div class="card-note">Embodied agents, agent harnesses, and agentic RL; VLA reward modeling and weak-to-strong distillation; dexterous manipulation and real-world data collection.</div></div><div class="card-date">Jun. 2026 – Present</div></div>

<div class="info-card"><div class="company-logo"><img src="{{ '/images/jd-academy.png' | relative_url }}" alt="JD Future Academy logo" loading="lazy"></div><div class="card-body"><div class="card-title">JD Future Academy · 京东探索研究院</div><div class="card-sub">Embodied AI Algorithm Development Intern</div><div class="card-note">Hierarchical VLM–VLA navigation, stateful embodied agents, simulation evaluation, and deployment on a quadruped robot.</div></div><div class="card-date">Mar. 2026 – Jun. 2026</div></div>

<div class="info-card"><div class="company-logo"><img src="{{ '/images/inkerbot-cropped.png' | relative_url }}" alt="LinkerBot logo" loading="lazy"></div><div class="card-body"><div class="card-title">LinkerBot · 灵心巧手</div><div class="card-sub">Algorithm Engineering Intern · Foundation Model Team</div><div class="card-note">Hand-object interaction and retargeting, vision-tactile-language-action policies, and robustness to changing camera viewpoints.</div></div><div class="card-date">Nov. 2025 – Mar. 2026</div></div>

## Education
{: #education }

<div class="info-card"><div class="card-badge"><img src="{{ '/images/ustb-badge.png' | relative_url }}" alt="USTB emblem" loading="lazy" width="50" height="50"></div><div class="card-body"><div class="card-title">University of Science and Technology Beijing</div><div class="card-sub">M.Sc. in Computer Science and Technology</div><div class="card-note">Admitted through recommendation · Advisor: Prof. Huimin Ma · Expected graduation: June 2027</div></div><div class="card-date">Sep. 2024 – Jun. 2027</div></div>

<div class="info-card"><div class="card-badge"><img src="{{ '/images/ustb-badge.png' | relative_url }}" alt="USTB emblem" loading="lazy" width="50" height="50"></div><div class="card-body"><div class="card-title">University of Science and Technology Beijing</div><div class="card-sub">B.Eng. in Computer Science and Technology</div></div><div class="card-date">Sep. 2020 – Jun. 2024</div></div>

## Honors & Awards
{: #honors }

<div class="award-grid">
  <div class="award-card level-region"><div class="award-meta"><span class="award-level">First Prize · Beijing</span><span class="award-date">2026</span></div><div class="award-name">“青创北京”2026年“挑战杯”首都大学生创业计划竞赛一等奖</div><div class="award-org">First Prize, Beijing “Challenge Cup” College Student Entrepreneurship Plan Competition</div></div>
  <div class="award-card level-school"><div class="award-meta"><span class="award-level">USTB</span></div><div class="award-name">Academic Star · 北京科技大学学术之星</div></div>
  <div class="award-card level-school"><div class="award-meta"><span class="award-level">USTB</span></div><div class="award-name">Outstanding Undergraduate Graduate · 北京科技大学优秀毕业生（本科）</div></div>
  <div class="award-card level-honor"><div class="award-meta"><span class="award-level">Scholarship</span></div><div class="award-name">National Scholarship · 国家奖学金</div></div>
  <div class="award-card level-national"><div class="award-meta"><span class="award-level">National</span></div><div class="award-name">iCAN Robotics Competition · iCAN 机器人竞赛</div><div class="award-org">National awards, twice</div></div>
</div>

## Coding & Open Source
{: #coding }

<div class="info-card">
  <div class="card-icon"><i class="fas fa-code" aria-hidden="true"></i></div>
  <div class="card-body">
    <div class="card-title">Embodied AI Chronicle · 具身智能大事纪</div>
    <div class="card-sub">A personal tool for keeping up with embodied AI</div>
    <div class="card-note">A searchable timeline of arXiv papers, robotics company blogs, industry news, and community discussions, with topic filters, trends, curated milestones, and automated updates.</div>
    <div class="card-links"><a href="https://roboherald.github.io/embodied-ai-chronicle/"><strong>Website</strong></a><a href="https://github.com/roboherald/embodied-ai-chronicle"><strong>Code</strong></a></div>
  </div>
</div>

## Skills
{: #skills }

- **Programming & frameworks:** Python, C++, PyTorch, JAX, Linux, ZeroMQ.
- **Robotics & simulation:** ROS / ROS2, Isaac Sim / Isaac Lab, MuJoCo, Habitat, LeRobot.
- **Research:** VLM / VLA, reinforcement and imitation learning, dexterous manipulation, navigation, sim-to-real transfer, and collaborative perception.

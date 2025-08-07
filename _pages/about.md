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

I am currently pursuing a master's degree at Southern University of Science and Technology, focusing on research in simulation EDA algorithms, high-performance numerical computing, and parallel computing.

I obtained my Bachelor's degree in Microelectronics Science and Engineering from the school of microelectronics, Southern University of Science and Technology([南方科技大学深港微电子学院](https://sme.sustech.edu.cn/en)) and am now studying for a master's degree in Integrated Circuit Science and Engineering at the same institute, advised by Professor Quan Chen([陈全](https://faculty.sustech.edu.cn/?tagid=chenq3&iscss=1&snapid=1&orderby=date&go=2&lang=en)).

My research interest includes: numerical integration, model order reduction, parallel acceleration, and sparse matrix solvers.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Two papers are accepted by ICCAD2025
- *2024.06*: &nbsp;🎉🎉 One paper is accepted by ICCAD2024
- *2024.03*: &nbsp;🎉🎉 One paper is accepted by ISEDA2024

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2025</div><img src='images/moment-match.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

EI-TR: A Versatile Exponential Integrator Framework for Transient Analysis of Generic Nonlinear Circuit

**Hang Zhou**, Zhenjie Lu, Quan Chen
- Aime to accelerate nonlinear circuit simulation by simplifying the computation in Newton-Raphson iterations.
- Propose a novel moment-matching strategy, achieving up to 23x speedup while improving numerical statbility, compared to traditional BDF method.
- Suitable for generic circuit simulation and straightforward for integration to commercial production code.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2025</div><img src='images/MF-MOR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MF-MOR: Multi-Fidelity Model Order Reduction for Many-Port Linear Systems in Chip Power Modeling

Zhenjie Lu, **Hang Zhou**, Quan Chen

- Extend traditional model order reduction to many-port linear systems using multi-fidelity modeling techniques.
- Compensate the low fidelity reduced order model by Neural Network trained from high fidelity simulation results.
- Achieve 27x speedup and Reduced model size by 47x on test cases with millons of nodes and thousands of ports, compared to traditional model order reduction techiniques.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2024</div><img src='images/EI-PIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

EI-PIT: A Parallel-in-Time Exponential Integrator Method for Transient Linear Circuit Simulation

**Hang Zhou**, Quan Chen

- Filled the blank of the parallel-in-time version of the exponential integrator method.
- Decouple time dependence by leverage the superposition principle of linear systems and the scaling invarience of exponential integrator.
- Achieve 2.5x speedup under 8 processes on benchmarks with millions of nodes.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISEDA 2024</div><img src='images/bbd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Parallel Acceleration Technique based on Bordered Block Diagonal Matrix Reordering for Exponential Integrator Method

**Hang Zhou**, Quan Chen

- Develop a paralle sparse matrix solver to accelerate forward/backward substitution based on BBD matrix reordering.
- Multi-threaded and multi-processed versions achieve 3.3x speedup under 16 threads and 2.0x speedup under 8 processes, respectively.
- The work was integrated to the commerical EDA tools of GuoWei FuXin Technology Co., Ltd.
</div>
</div>


# 🎖 Honors and Awards
- **First Prize**, Outstanding Research Assistant Scholarship, SUSTECH, *2023-2024*
- **First Prize**, Outstanding Academic Scholarship, SUSTECH, *2023-2024*
- **First Prize**, "Capstone Design" Project Exhibition, College of Engineering, SUSTECH, *2023* 
- **Outstanding Undergraduate Thesis**, SUSTECH, *2023*
- **Second Prize**, 12th National College Student Mathematics Competition (Non-Math Major), *2021*
- **Second Prize**, Excellent Student Scholarship, SUSTECH, *2019-2020*

# 📖 Educations
- *2023.09 - 2026.07 (expected)*, Master, School of Microelectronics, Southern University of Science and Technology
- *2019.09 - 2023.07*, Undergraduate, School of Microelectronics, Southern University of Science and Technology

# 💬 Patents
**Quan Chen**, Dongen Yang, **Hang Zhou**, et al.
- Acceleration Method for Transient Circuit Simulation
- Chinese Patent [CN117556767A](https://patents.google.com/patent/CN117556767A/en), **Filed**, February 2024. (*third inventor*)

**Quan Chen**, **Hang Zhou**, et al.
- Method and System for Large-Scale Linear Circuit Simulation
- Chinese Patent [CN117077607A](https://patents.google.com/patent/CN117077607A/en), **Granted**, June 2024. (*second inventor*)

# 💻 Internships
- *2025.01 - 2025.07*, [Shenzhen BTD Technology Co., Ltd.](https://www.btd.tech/), Shenzhen, China.
- *2025.07 - 2025.08*, [Dongfeng Motor Co., Ltd. Dongfeng Nissan Passenger Vehicle Company](https://www.dongfeng-nissan.com.cn/), Guangzhou, China

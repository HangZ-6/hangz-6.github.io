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

I am a master's student at the [Southern University of Science and Technology (SUSTech, 南方科技大学)](https://www.sustech.edu.cn/en/), working with Prof. [**Quan Chen (陈全)**](https://faculty.sustech.edu.cn/?tagid=chenq3&iscss=1&snapid=1&orderby=date&go=2&lang=en) on EDA algorithms and high-performance numerical methods. My research focuses on simulation acceleration for integrated circuits, with emphasis on exponential integrators, parallel computing, and model order reduction.

I received my B.S. in Microelectronics Science and Engineering from the [School of Microelectronics, SUSTech (南方科技大学深港微电子学院)](https://sme.sustech.edu.cn/en), and I am currently pursuing an M.S. in Integrated Circuit Science and Engineering at the same institute.

My core interests include:
- Exponential integrator methods
- Numerical stability and regularization
- Parallel and distributed simulation frameworks
- Model order reduction (MOR) for large-scale systems
- Sparse matrix solvers and reordering techniques


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Two papers are accepted by ICCAD2025
- *2024.06*: &nbsp;🎉🎉 One paper is accepted by ICCAD2024
- *2024.03*: &nbsp;🎉🎉 One paper is accepted by ISEDA2024

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><a href="https://ieee-ceda.org/publications/tcad" style="color: white;">TCAD</a></div><img src='images/implicit reg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

An Implicit Regularization Technique for Exponential Integrator in Generic Transient Circuit Simulation(**Under Review**)

**Hang Zhou**, Zhenjie Lu, Quan Chen
- Identified the fundamental cause of numerical instability in exponential integrator methods.  
- Introduced *static mode synchronization* and *dynamic mode rectification*, enhancing robustness with negligible computational overhead.  
- Validated on industry-scale benchmarks, demonstrating stable performance without sacrificing efficiency.  
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><a href="https://2025.iccad.com/" style="color: white;">ICCAD 2025</a></div><img src='images/moment-match.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

EI-TR: A Versatile Exponential Integrator Framework for Transient Analysis of Generic Nonlinear Circuit(**Accepted**)

**Hang Zhou**, Zhenjie Lu, Quan Chen
- Proposes a novel moment-matching strategy to reduce the cost of Newton-Raphson iterations.  
- Achieves up to **23× speedup** with improved numerical stability compared to BDF methods.  
- Easily integrates into commercial EDA tools.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><a href="https://2025.iccad.com/" style="color: white;">ICCAD 2025</a></div><img src='images/MF-MOR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MF-MOR: Multi-Fidelity Model Order Reduction for Many-Port Linear Systems in Chip Power Modeling(**Accepted**)

Zhenjie Lu, **Hang Zhou**, Quan Chen

- Enhances traditional MOR with neural-network compensation trained on high-fidelity data.  
- Achieves **27× speedup** and **47× model size reduction** for large many-port circuits. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><a href="https://2024.iccad.com/" style="color: white;">ICCAD 2024</a></div><img src='images/EI-PIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EI-PIT: A Parallel-in-Time Exponential Integrator Method for Transient Linear Circuit Simulation](https://doi.org/10.1145/3676536.3676785)

**Hang Zhou**, Quan Chen
- Introduces the first parallel-in-time framework for exponential integrators.  
- Leverages superposition and scaling invariance to decouple time dependency.  
- Achieves **2.5× speedup** on 8-core machines.  
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><a href="https://www.eda2.com/iseda2024/index.html" style="color: white;">ISEDA 2024</a></div><img src='images/bbd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Parallel Acceleration Technique based on Bordered Block Diagonal Matrix Reordering for Exponential Integrator Method](https://doi.org/10.1109/ISEDA62518.2024.10617631)

**Hang Zhou**, Quan Chen

- Implements a parallel solver for sparse triangular systems using BBD reordering.  
- Achieves **3.3× speedup** (OpenMP) and **2.0× speedup** (MPI).  
- Integrated into GuoWei FuXin’s commercial EDA tools.  
</div>
</div>


# 🎖 Honors and Awards
- 🥇 Outstanding Research Assistant Scholarship, SUSTECH, *2023-2024*
- 🥇 Outstanding Academic Scholarship, SUSTECH, *2023-2024*
- 🥇 First Prize, "Capstone Design" Project Exhibition, College of Engineering, SUSTECH, *2023* 
- 🏅 Outstanding Undergraduate Thesis, SUSTECH, *2023*
- 🥈 Second Prize, 12th National College Student Mathematics Competition (Non-Math Major), *2021*
- 🥈 Excellent Student Scholarship, SUSTECH, *2019-2020*

# 📖 Educations
- **M.S.** in Integrated Circuit Science and Engineering  
  *Southern University of Science and Technology* (2023.09 – 2026.07, expected)  
- **B.S.** in Microelectronics Science and Engineering  
  *Southern University of Science and Technology* (2019.09 – 2023.07)

# 💡 Patents
- **Method and System for Large-Scale Linear Circuit Simulation**  
  Chinese Patent [CN117077607A](https://patents.google.com/patent/CN117077607A/en), **Granted**, June 2024 (*Second Inventor*)

- **Acceleration Method for Transient Circuit Simulation**  
  Chinese Patent [CN117556767A](https://patents.google.com/patent/CN117556767A/en), **Filed**, February 2024 (*Third Inventor*)


# 💻 Internships
- [**Shenzhen BTD Technology Co., Ltd.**](https://www.btd.tech/)  
  Shenzhen, China (2025.01 – 2025.07)  
- [**Dongfeng Nissan Passenger Vehicle Company**](https://www.dongfeng-nissan.com.cn/)  
  Guangzhou, China (2025.07 – 2025.08)

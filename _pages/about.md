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
- Aimed to accelerate nonlinear circuit simulation by simplifying the computation in Newton-Raphson iterations.
- Proposed a novel moment-matching strategy, achieving up to 23x speedup while improving numerical statbility, compared to traditional BDF method.
- Suitable for generic circuit simulation and straightforward for integration to commercial production code.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2025</div><img src='images/MF-MOR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MF-MOR: Multi-Fidelity Model Order Reduction for Many-Port Linear Systems in Chip Power Modeling

Zhenjie Lu, **Hang Zhou**, Quan Chen

- Extended traditional model order reduction to many-port linear systems using multi-fidelity modeling techniques.
- Compensate the low fidelity reduced order model by Neural Network trained from high fidelity simulation results.
- Achieved 27x speedup and Reduced model size by 47x on test cases with millons of nodes and thousands of ports, compared to traditional model order reduction techiniques.
</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

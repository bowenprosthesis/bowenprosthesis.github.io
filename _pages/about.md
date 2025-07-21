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

I am a Ph.D. student at Harbin Institute of Technology, with research interests in the design and control of prosthetic and robotic systems, and gait analysis. 

# 🔧 Projects 

### *1. Design of an EHA-Driven Powered Ankle-Foot Prosthesis*  

<img src="images/Gen_123.png" alt="Figure: Gen image" width="70%">

> Hydraulic systems are well-suited for designing highly integrated, high-load-capacity drive systems. We developed **three generations** of EHA-driven ankle-foot prostheses to improve power density and biomechanical adaptability:
  
  - [**Gen-1**](https://raw.githubusercontent.com/bowenprosthesis/bowenprosthesis.github.io/main/images/Gen-1.png): Off-board, damping-based hydraulic system  
  - [**Gen-2**](https://raw.githubusercontent.com/bowenprosthesis/bowenprosthesis.github.io/main/images/Gen-2.png): Fully active, on-board direct-drive design  
  - [**Gen-3**](https://raw.githubusercontent.com/bowenprosthesis/bowenprosthesis.github.io/main/images/AMAM_poster.png): Fully active prosthesis with hydraulic-based *Serial Elastic Actuation (SEA)*

  The evolution demonstrates a shift from passive damping to **actively controlled, biomimetic actuation**, enhancing both performance and compactness.

**Supervisor**: Prof. [Qitao Huang](https://homepage.hit.edu.cn/huangqitao)


### *2. Study on the Biomechanical Impact of a Powered Biarticular prothetic foot*  
![Figure: Bypass image](images/bypassStudy.png)
 > Conventional ankle-foot prostheses primarily replicate monoarticular muscle functions (e.g., Soleus, Tibialis Anterior), but often fail to capture the contributions of biarticular muscles such as the Gastrocnemius. We developed a powered prosthetic foot incorporating a cable-driven biarticular muscle actuator. Experiments with healthy participants demonstrated a reduction in metabolic cost. We analyzed potential contributing factors, including joint mechanics, center-of-mass dynamics, and gait symmetry.

[**Publication**](https://doi.org/10.1016/j.jbiomech.2025.112768)

**Collaborators**: Martin Grimmer, Julian Zeiss, Florian Weigand

### *3. User Preference-Based Human-in-the-Loop Tuning of Exoskeleton Assistance during Walking*  
 > Recent studies have demonstrated that human-in-the-loop (HIL) optimization can generate individualized exoskeleton control parameters to reduce metabolic cost. However, the time-consuming nature of this process limits its practical use, particularly for older adults and patients. Meanwhile, humans have shown the ability to adapt gait to different assistance profiles over time, leading to reduced metabolic expenditure. This project investigates a user-driven, self-tuning control strategy based on subjective perception, aiming to achieve metabolic reduction without complex optimization algorithms.

[**Conference paper**](https://doi.org/10.18910/92286)

**Collaborators**: Guoping Zhao, Niklas Schaefer

### *4. Design of a Biped Walking Robot*  
![Figure: Bipedal image](images/guroatom.png)
 > We are developing a bipedal walking robot equipped with a 1-DoF waist joint, 3-DoF hip joints, 1-DoF knees, and 2-DoF ankles, providing comprehensive lower-limb mobility. The robot serves as a research platform for humanoid locomotion, dynamic balance control, and assistive walking strategies.

**Collaborators**: Guoping Zhao, Fan Yang, Yelin Jiang
  
# 🎖 Honors and Awards
- *2020*, China National Scholarship for Academic Excellence  
- *2022*, CSC Scholarship by China Scholarship Council for Overseas Study

# 📖 Educations
- *2021.09 - present*, Ph.D. in Mechanical Engineering, Harbin Institute of Technology, China  
- *2019.09 - 2021.06*, M.Eng. in Mechanical Engineering, Harbin Institute of Technology, China  
- *2011.09 - 2015.06*, B.Eng. in Mechanical Engineering, Northeastern University, China

# 💼 Work Experience
- *2015.07 - 2018.04*, Engineer, Shenyang Machine Tool Group, China  
  Responsible for the development and testing of CNC systems for machine tools. 

# 📚 Visiting
- *2022.10 – 2023.10*, Visiting Student, Lauflabor, TU Darmstadt, Germany  
  Conducted joint research on biomechanical analysis and lower-limb exoskeleton control.

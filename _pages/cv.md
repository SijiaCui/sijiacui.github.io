---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Pattern Recognition and Intelligent Systems, Institute of Automation, Chinese Academy of Sciences, 2022.09 – 2027.06 (expected)
  * State Key Laboratory of Cognition and Decision Intelligence for Complex Systems
  * GPA 3.7/4.0; Outstanding Student Award
* B.E. in Computer Science and Technology, Shandong University (Taishan Scholar Class), 2018.09 – 2022.06
  * GPA 3.8/4.0, rank 5/17; academic scholarship

Work experience
======
* 2025.11 – : Post-training Algorithm Intern, Alibaba Qwen (RLHF)
  * Multi-expert on-policy distillation (MOPD) merging with 35B–397B experts
  * Self-play for VLM hallucination detection; CLIPO contrastive RLVR

* 2024.11 – 2025.07: Algorithm Intern, Zhipu AI
  * Real-user function-calling benchmark; agent post-training with VERL (+9% on internal eval)

Skills
======
* Post-training: VERL, SLIME; large-scale RL, multi-expert OPD
* LLM agents: memory, skills, function calling, planning
* Data synthesis: seed data construction, data mixing
* Programming: Python, C, C++, Java, Shell, Docker, SQL

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Contact
======
* Email: [cuisijiax@163.com](mailto:cuisijiax@163.com)
* GitHub: [@SijiaCui](https://github.com/SijiaCui)
* Google Scholar: [profile](https://scholar.google.com/citations?user=QUjaAiwAAAAJ)

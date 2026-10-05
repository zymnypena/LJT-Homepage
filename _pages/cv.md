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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology (HKUST), 2024–Present
  * HKUST NLP Group; Supervisor: Professor Junxian He.
* B.Eng., Shanghai Jiao Tong University (SJTU), 2020–2024
  * Graduated June 2024.
* Award: Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

Research Experience
======
* February 2025 – Present: Research Intern, MINIMAX.
* June 2024 – September 2024: Research Intern, Tencent WXG; Advisor: Zifei Shan.
* June 2023 – December 2023: Research Intern, Shanghai AI Lab; Advisor: Prof. Yu Cheng.

Skills / Research Interests
======
* Natural Language Processing (NLP)
* Machine Learning (ML)
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

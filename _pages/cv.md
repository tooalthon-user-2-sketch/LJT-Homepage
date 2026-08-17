---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* Ph.D. in Computer Science, Hong Kong University of Science and Technology (HKUST), 2024–Present
  * HKUST NLP Group, advised by Prof. Junxian He

* B.Eng. in Computer Science, Shanghai Jiao Tong University (SJTU), 2020–2024
  * Received the Zhiyuan Honor Scholarship

## Research Experience

* **Research Intern** — MINIMAX, February 2025 – Present

* **Research Intern** — Tencent WXG, June 2024 – September 2024
  * Advised by Zifei Shan

* **Research Intern** — Shanghai AI Lab, June 2023 – December 2023
  * Advised by Prof. Yu Cheng

## Skills

* Natural Language Processing
* Machine Learning
* Python, PyTorch

## Awards

* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Full Publication List

{% for post in site.publications reversed %}
  * {{ post.citation }}
{% endfor %}

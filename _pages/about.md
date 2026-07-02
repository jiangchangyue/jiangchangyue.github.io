---
permalink: /
title: "Changyue Jiang (蒋昌跃)"
description: "Changyue Jiang (蒋昌跃) is a Ph.D. student at Fudan University and Shanghai Innovation Institute working on AI Security and AI Safety."
keywords: "Changyue Jiang, 蒋昌跃, Fudan University, Shanghai Innovation Institute, AI Security, AI Safety, Agent Safety, RAG Security"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I’m a Ph.D. student at Fudan University (复旦大学) and Shanghai Innovation Institute (SII, 上海创智学院), advised by Prof. Min Yang (杨珉) and Prof. Xudong Pan (潘旭东).
My research interests include AI Security and AI Safety.

Email: cyjiang24@m.fudan.edu.cn

Research Interests
======
- AI Security
- AI Safety
- Agent Safety
- RAG Security

Publications
======
{% include publication-list.html %}

See the <a href="/publications/">Publications</a> page for publication details.

<h2 id="projects">Open Source Projects</h2>
{% for project in site.data.projects %}
  {% include project-card.html %}
{% endfor %}

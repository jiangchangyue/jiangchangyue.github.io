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
* Ph.D. student, Fudan University and Shanghai Innovation Institute, 2024-present

Research interests
======
* AI Security
* AI Safety
* Agent Safety
* RAG Security

Publications
======
  <ul>
  {% assign publication_order = "Think Twice Before You Act|MATE: Policy-Aware Security Auditing|MirrorGuard: Toward Secure Computer-Use Agents|Feedback-Guided Extraction" | split: "|" %}
  {% for ordered_title in publication_order %}
    {% for post in site.publications %}
      {% if post.title contains ordered_title %}
        {% include archive-single-cv.html %}
      {% endif %}
    {% endfor %}
  {% endfor %}
  </ul>

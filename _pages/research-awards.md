---
layout: archive
title: "Research & Awards"
permalink: /research-awards/
author_profile: true
---

Research Interests
------

Causal Inference and Missing Data Problems
Semi-supervised Inference
High Dimensional Statistics
Machine Learning
Dynamic Treatment Regimes and Reinforcement Learning

Presentations
------
{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

---
layout: archive
title: "About"
permalink: /
author_profile: true
---

<section class="research-hero" aria-label="Research overview">
  <p class="research-eyebrow">Ph.D. Student · Sejong University</p>
  <h2>Privacy-preserving<br>machine learning.</h2>
  <p class="research-lead">Exploring encrypted computation and collaborative learning with fully homomorphic encryption.</p>
  <div class="profile-actions">
    <a class="profile-action profile-action--primary" href="https://www.linkedin.com/in/dokyeong-kang-ba3b09437/"><i class="fab fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
    <a class="profile-action" href="https://github.com/Hidogyeong"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    <a class="profile-action" href="https://scholar.google.com/citations?user=8SUaCMkAAAAJ&amp;hl=en">Google Scholar</a>
  </div>
</section>

I am a **Ph.D. student at Sejong University, South Korea**. My research focuses on **fully homomorphic encryption (FHE)**, particularly **CKKS** and **privacy-preserving federated learning**.

I am also interested in secure multi-party computation (MPC) and private machine learning inference. My previous research explored wearable radar–IMU sensor fusion for hand gesture recognition under head motion.

## Research interests

<ul class="research-topics">
{% for interest in site.data.cv.interests %}
  <li>{{ interest }}</li>
{% endfor %}
</ul>

## Selected publication

{% assign paper = site.data.publications | first %}
{% include publication-entry.html paper=paper %}

## From research to implementation

<div class="research-work">
  <div>
    <h3>Encrypted learning</h3>
    <p>CKKS-based federated learning experiments with <strong>Python, PyTorch, C++, and OpenFHE</strong>.</p>
  </div>
  <div>
    <h3>Wearable sensing</h3>
    <p>Radar–IMU fusion for gesture recognition under head motion, from data processing to model training and evaluation.</p>
    <a href="https://github.com/Hidogyeong/Label-efficient-head-motion-robust-wearable-radar-HGR-via-motion-domain-radar-IMU-fusion">Explore research code &rarr;</a>
  </div>
</div>

<p class="profile-contact">Find my research background in my <a href="{{ '/cv/' | relative_url }}">CV</a>, or connect with me on <a href="https://www.linkedin.com/in/dokyeong-kang-ba3b09437/">LinkedIn</a>.</p>

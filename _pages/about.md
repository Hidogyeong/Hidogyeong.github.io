---
layout: archive
title: "About"
permalink: /
author_profile: true
---

I am a **Ph.D. student at Sejong University, South Korea**. I study fully homomorphic encryption (FHE), with a focus on CKKS and privacy-preserving federated learning.

I am also interested in secure multi-party computation (MPC) and private machine learning inference. My previous research explored wearable radar–IMU sensor fusion for hand gesture recognition under head motion.

## Research interests

{% for interest in site.data.cv.interests %}
- {{ interest }}
{% endfor %}

## Selected publication

{% assign paper = site.data.publications | first %}
{% include publication-entry.html paper=paper %}

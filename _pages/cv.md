---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
---

## Education

{% for entry in site.data.cv.education %}
**{{ entry.qualification }} — {{ entry.institution }}**  
{{ entry.location }}{% if entry.period %} · {{ entry.period }}{% endif %}
{% endfor %}

## Research interests

{% for interest in site.data.cv.interests %}
- {{ interest }}
{% endfor %}

## Research experience

{% for entry in site.data.cv.research %}
### {{ entry.title }}

{{ entry.description }}{% if entry.url %} [Code]({{ entry.url }}){% endif %}

{% endfor %}

## Technical experience

{% for skill in site.data.cv.skills %}
- **{{ skill.name }}:** {% if skill.url %}[{{ skill.description }}]({{ skill.url }}){% else %}{{ skill.description }}{% endif %}
{% endfor %}

## Publications

{% for paper in site.data.publications %}
{% include publication-entry.html paper=paper compact=true %}
{% endfor %}

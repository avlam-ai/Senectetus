---
layout: default
title: "Senectetus"
---

# Practical Resilience for Today’s Challenges
Essays on how wisdom from Seneca and Epictetus can be applied to everyday life.

## About Senectetus
Senectetus draws inspiration from the writings of Seneca and Epictetus, but transcends their works to explore how ancient wisdom can be applied to the complexities of modern life. Through essays and reflections, we bridge the gap between Stoic philosophy and today’s challenges—helping you find clarity, resilience, and purpose in an ever-changing world.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}



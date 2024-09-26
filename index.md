---
layout: default
title: "Senectetus"
---

### **"Senectetus: Timeless Wisdom for the Modern Mind"**

### About Senectetus:
Senectetus began by drawing inspiration from the writings of Seneca and Epictetus, but transcends their works to explore how ancient wisdom can be applied to the complexities of modern life. Through essays and reflections, this resource aims to help you find clarity, resilience, and purpose in an ever-changing world. This is a space where timeless philosophical concepts are made accessible and relevant to contemporary life.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}



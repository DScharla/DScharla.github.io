---
layout: home
title: Home
---

Welcome! Each week I set a goal 🎯, plan how to learn it, build something, and reflect on the process.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
- **Week:** {{ post.week | default: "—" }}
- **Goal:** {{ post.goal | default: "—" }}
- **Outcome:** {{ post.outcome | default: "—" }}
- **Tags:** {% for tag in post.tags %}`{{ tag }}` {% endfor %}

{{ post.excerpt }}
<hr/>
{% endfor %}

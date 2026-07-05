---
layout: default
title: Home
---

# Welcome to My Portfolio

I'm **Robert MacKay, P.Eng.**, a Professional Engineer specializing in instrumentation, control systems, and automation engineering across nuclear energy, oil & gas, and petrochemical sectors.

## About Me

With 10+ years of experience, I design and deploy critical Distributed Control Systems (DCS), fiber optic infrastructure, and process automation solutions. I'm currently leading control systems development for the **BWRX-300 small modular reactor** at GE Vernova's Darlington Nuclear Power Plant.

**Key Expertise:**
- Nuclear facility control systems and IEC 61513 compliance
- DCS architecture design (Allen-Bradley ControlLogix, DeltaV)
- Large-scale industrial projects across Canada
- Team leadership and technical project delivery

## Featured Projects

Explore my [complete project portfolio](/projects/) showcasing major initiatives in nuclear energy, oil & gas infrastructure, and automation systems.

## Latest Articles

{% for post in site.posts limit:3 %}
<div class="post-card">
  <div class="post-date">{{ post.date | date: "%B %d, %Y" }}</div>
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p class="post-excerpt">{{ post.excerpt }}</p>
  <a href="{{ post.url | relative_url }}" class="read-more">Read More →</a>
</div>
{% endfor %}

<p><a href="/blog/">View all articles →</a></p>

## Connect

- **LinkedIn:** [linkedin.com/in/robertjamesmackay](https://linkedin.com/in/robertjamesmackay)
- **GitHub:** [github.com/robertmackayeng](https://github.com/robertmackayeng)
- **Email:** robert.james.mackay@outlook.com
- **Professional License:** P.Eng., Professional Engineers Ontario (PEO)

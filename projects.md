---
layout: default
title: Projects
---

<link rel="stylesheet" href="/assets/css/style.css">

# Projects

{% assign items = site.projects | sort: "title" %}

{% for p in items %}
<div class="project-card">
  <h3 style="margin-top:0;">
    <a href="{{ p.url }}">{{ p.title }}</a>
  </h3>

  {% if p.summary %}
    <p style="margin-top:10px; opacity:0.95;">{{ p.summary }}</p>
  {% else %}
    <p style="margin-top:10px; opacity:0.75;">
      <i>No summary found yet. Add <code>summary:</code> to this project’s front matter.</i>
    </p>
  {% endif %}

  {% if p.skills %}
  <div class="badges">
    {% for s in p.skills %}
      <span class="badge">{{ s }}</span>
    {% endfor %}
  </div>
  {% endif %}

  <div style="margin-top:12px;">
    <a class="btn" href="{{ p.url }}">Read Summary</a>
    {% if p.pdf %}
      <a class="btn" href="{{ p.pdf }}">Read Full Report (PDF)</a>
    {% endif %}
  </div>
</div>
{% endfor %}

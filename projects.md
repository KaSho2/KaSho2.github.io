<link rel="stylesheet" href="/assets/css/style.css">

# All Projects

{% for p in site.projects %}
<div class="project-card">
  <h3><a href="{{ p.url }}">{{ p.title }}</a></h3>
  <p>{{ p.summary }}</p>

  {% if p.skills %}
  <div class="badges">
    {% for s in p.skills %}
      <span class="badge">{{ s }}</span>
    {% endfor %}
  </div>
  {% endif %}

  <a class="btn" href="{{ p.url }}">Read Summary</a>
  {% if p.pdf %}
    <a class="btn" href="{{ p.pdf }}">Read Full Report (PDF)</a>
  {% endif %}
</div>
{% endfor %}
---
layout: default
title: "Galería de Prompts"
---

<h2>Prompts disponibles</h2>
<div class="cards">
{% for prompt in site.prompts %}
  <div class="prompt-card">
    <h3><a href="{{ prompt.url }}">{{ prompt.title }}</a></h3>
    <p>{{ prompt.excerpt }}</p>
    <p>
      {% for tag in prompt.tags %}
        <span class="tag">{{ tag }}</span>
      {% endfor %}
    </p>
    <a href="{{ prompt.url }}">Ver detalle</a>
  </div>
{% endfor %}
</div>
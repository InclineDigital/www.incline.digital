---
title: ◢ Incline Customers
headline: Happy Clients
---

<ul class="logos">
{% for logo in site.static_files  %}
  {% if logo.path contains "assets/images/logos" %}
   <li><img src="{{ logo.path }}" alt="{{ logo.basename | replace: "_", " " | capitalize }}" /></li>
  {% endif %}
{% endfor %}
</ul>

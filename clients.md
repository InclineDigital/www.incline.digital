---
title: ◢ Incline Clients
headline: Happy Customers
description: Incline has had the opportunity to work with some amazing clients, large and small. Incline offers digital consulting services focused around web apps, automation, and optimization.
permalink: clients/
---

<ul class="logos">
{% for logo in site.static_files  %}
  {% if logo.path contains "assets/images/logos" %}
   <li><img src="{{ logo.path }}" alt="{{ logo.basename | replace: "_", " " | capitalize }}" /></li>
  {% endif %}
{% endfor %}
</ul>


[Work with Incline](/) and add your logo to the list!

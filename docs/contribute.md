---
title: Contribute
nav_order: 35
---

# Contribute to Aisleron

## GitHub Contributors

Thank you to these amazing people who have contributed to Aisleron with code or translations.

<div class="contributors-grid">
  {% if site.data.contributors %}
    {% for person in site.data.contributors %}
      <a href="{{ person.html_url }}" target="_blank" rel="noopener noreferrer">
        <img src="{{ person.avatar_url }}&s=64" alt="{{ person.login }}" title="{{ person.login }}" style="width: 50px; height: 50px; border-radius: 50%; margin: 5px; border: 2px solid #e1e4e6;">
      </a>
    {% endfor %}
  {% endif %}
</div>

## Get Involved

If you would like to help make Aisleron better, or just want your mugshot included on the list, see the links below for ways to contribute.

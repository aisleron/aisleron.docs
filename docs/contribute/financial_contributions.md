---
title: Financial Contributions
parent: Contribute
nav_order: 50
redirect_from:
  - /docs/contribute/donate
---

# Financial Contributions

Aisleron's mission is to make everyone's shopping experience faster and more convenient, so you can spend more time on the things that truly matter to you. That is all the motivation we need to keep going.

If, after reading that, you are still willing and able to contribute financially, it would be much appreciated. Your contribution will be used to further our mission and to make Aisleron even better. You can support us through:


[![GitHub Logo](/assets/images/app-tool-icons/GitHub.png){: .v-align-middle width="32" style="margin-right: 6px;"} GitHub Sponsors](https://github.com/sponsors/aisleron){: .btn .v-align-middle}

## Financial Supporters

Thank you to these awesome folks who have supported Aisleron's development with financial contributions.

<div class="sponsors-grid">
  {% if site.data.sponsors %}
    {% for person in site.data.sponsors %}
      <a href="{{ person.html_url }}" target="_blank" rel="noopener noreferrer">
        <img src="{{ person.avatar_url }}&s=64" alt="{{ person.login }}" title="{{ person.login }}" style="width: 50px; height: 50px; border-radius: 50%; margin: 5px; border: 2px solid #e1e4e6;">
      </a>
    {% endfor %}
  {% endif %}
</div>
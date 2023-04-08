---
layout: default
title: Home
nav_order: 1
description: "Beth's Anti-Transphobia Library is a collection of resources for combating online transphobia."
permalink: /
---

# Beth's Anti-Transphobia Library
{: .fs-9 }

*[BATL]: Beth's Anti-Transphobia Library

BATL transphobia online with this handy collection of resources.
{: .fs-6 .fw-300 }

## About the project

BATL is &copy; 2023-{{ "now" | date: "%Y" }} by [Beth](https://twitter.com/bethylamine).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change.

#### Contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

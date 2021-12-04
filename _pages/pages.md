---
author_profile: false
layout: archive
permalink: /pages
title: "Pages"
---

{% for post in site.pages %}
    {% unless post.hidden %}
        {% include archive-single.html %}
    {% endunless %}
{% endfor %}

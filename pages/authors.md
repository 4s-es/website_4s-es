---
layout: default
permalink: /author/index.html 
title: Autoren
---

<ul>
    {% for author in site.data.authors %}
        <li>
            <a href="{{ author.permalink }}">
                {{ author.display_name }}
            </a>
        </li>
    {% endfor %}
</ul>

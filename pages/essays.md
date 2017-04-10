---
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "Lorem ipsum dolor sit amet."
title: Esee
permalink: /essays
css:
  - /assets/essay_tiles.css
---

<h2 id="Esee">Posts</h2>

<div id="twoColumns">
        {% for post in site.posts %}
            <div class="tile">
                <div class="tileTitle">{{ post.date | date: "%d %B %Y" }}&mdash; <a href="{{ post.url }}">{{ post.title }}</a> </div>
                <img src="{{post.image}}"/>
                <p>{{ post.description }}</p>
            </div>
        {% endfor %}
</div>
---
id: essay
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "essay,esee"
title: Esee
permalink: /essay
css:
  - /assets/css/essay_tiles.css
---
<div class="essay-wrapper">
    <div class="essay-columns">
        {% for post in site.posts %}
	        <div class="essay-tile">
	            <div class="essay-title"><a href="{{ post.url }}">{{ post.title }}</a></div>
	            <div class="essay-date">{{ post.date | date: "%d %B %Y" }}</div>
	            <p>{{ post.description }}</p>
	            <a href="{{ post.url }}"><img src="{{ post.image.url }}"/></a>
	        </div>
	    {% endfor %}
	</div>
</div>
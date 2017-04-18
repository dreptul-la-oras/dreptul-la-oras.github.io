---
id: essay
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "essay,esee"
title: Esee
permalink: /writings.html
css:
  - /assets/css/writings_tiles.css
---
<div class="writings-wrapper">
    <div class="writings-columns">
        {% for post in site.posts %}
	        <div class="writings-tile">
	            <div class="writings-title"><a href="{{ post.url }}">{{ post.title }}</a></div>
	            <div class="writings-date">{{ post.date | date: "%Y-%m-%d" }}</div>
	            <p>{{ post.description }}</p>
	            <a href="{{ post.url }}"><img src="{{ post.image.url }}"/></a>
	        </div>
	    {% endfor %}
	</div>
</div>
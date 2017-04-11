---
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "Lorem ipsum dolor sit amet."
title: Esee
permalink: /essay
css:
  - /assets/css/essay_tiles.css
---

<h2>Esee</h2>

<div id="wrapper">
    <div id="columns">
        {% for post in site.posts %}
	        <div class="pin">
	            <div class="pinTitle">{{ post.date | date: "%d %B %Y" }}  &mdash; <a href="{{ post.url }}">{{ post.title }}</a></div>
	            <p>{{ post.description }}</p>
               <img src="{{ post.image }}"/>
	        </div>
	    {% endfor %}
	</div>
</div>
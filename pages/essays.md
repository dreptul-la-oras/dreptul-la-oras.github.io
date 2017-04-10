---
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "Lorem ipsum dolor sit amet."
title: Esee
permalink: /essays
---

<h2 id="Esee">Posts</h2>

<div>
    <ul>
        {% for post in site.posts %}
           <li><span>{{ post.date | date: "%d %B %Y" }}&mdash; <a href="{{ post.url }}">{{ post.title }}</a> </span> 
                <p>{{ post.description }}</p>
           </li>
        {% endfor %}
    </ul>
</div>
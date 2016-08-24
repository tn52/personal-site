---
layout: page
permalink: /food/
title: food
description: I love food. (I don't take favorites. I like all kinds of food.)
---

{% for food in site.food %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ food.url }}">
        {% if food.img %}
        <img class="thumbnail" src="{{ food.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ food.title }}</h1>
            <br/>
            <p>{{ food.description }}</p>
        </span>
        </a>
    </div>
</div>


{% endfor %}
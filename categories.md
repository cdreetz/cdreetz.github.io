---
layout: default
title: Categories
permalink: /categories/
---

<div class="blog list">
    <h1>Filed Under <small>#{{ category | first }}</small></h1>

	{% for category in site.categories %}
	    <div class="categories-title"><a href="/tags/#{{ category | first }}">{{ category | first }}</a></div>   
	{% endfor %}

</div>

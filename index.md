---
title: Home
layout: default
---

<ul class="posts">
{% for post in site.posts %}
	<li><a href="{{ post.url }}">{{ post.title}}</a>
		<span class="posts-date">{{ post.date | date: "%b %-d, %Y" }}</span>
	</li>
{% endfor %}
</ul>

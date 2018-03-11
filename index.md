---
title: chrisbowman.design
layout: default
---

<div class="posts">
{% for post in site.posts %}
	<article>
		<a href="{{ post.url }}">{{ post.title}}</a>
		<span class="posts-date">{{ post.date | date: "%b %-d, %Y" }}</span>
		<div class="excerpt">{{ post.excerpt }}</div>
	</article>
{% endfor %}
</div>

<div class="aside">
	<h2>Who?</h2>
	<p>Hi, I am Chris; professor, logo designer, UI specialist, and VP design & dev at Sprout Studio.</p>
</div>

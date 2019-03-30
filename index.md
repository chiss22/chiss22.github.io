---
title: Hi, I am Chris; professor, logo designer, UI specialist, and VP design & dev at Sprout Studio.
layout: default
---

<blog>
{% for post in site.posts %}
	<article>
		<h2><a href="{{ post.url }}">{{ post.title}}</a></h2>
		<span class="posts-date">{{ post.date | date: "%b %-d, %Y" }}</span>
	</article>
{% endfor %}
</blog>

<aside>
	<h2>Who?</h2>
	<p>Hi, I am Chris; professor, logo designer, UI specialist, and VP design & dev at Sprout Studio.</p>
</aside>

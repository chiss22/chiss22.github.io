---
title: Hi, I am Chris; professor, logo designer, UI specialist, and VP design & dev at Sprout Studio.
layout: default
---

<blog>
{% for post in site.posts %}
	<article>
		<h2><a href="{{ post.url }}">{{ post.title}}</a></h2>
		<date>{{ post.date | date: "%b %-d, %Y" }}</date>
		<content>{{ content }}</content>
	</article>
{% endfor %}
</blog>

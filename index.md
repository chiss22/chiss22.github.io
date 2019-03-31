---
title: Hi, I am Chris; professor, logo designer, UI specialist, and VP design & dev at Sprout Studio.
layout: default
---

<section>
	<blog>
	{% for post in site.posts %}
		<article>
			<h2><a href="{{ post.url }}">{{ post.title}}</a></h2>
			<span class="posts-date">{{ post.date | date: "%b %-d, %Y" }}</span>
			{{ content }}
		</article>
	{% endfor %}
	</blog>
</section>
<aside>
	<h3>Archives</h3>
	<ul>
	{% for post in site.posts %}
		<li><a href="{{ post.url }}">{{ post.title}}</a></li>
	{% endfor %}
	</ul>
</aside>

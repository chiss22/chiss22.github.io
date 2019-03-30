---
title: CBD
layout: default
---

<div class="posts">
{% for post in site.posts %}
	<article>
		<h2><a href="{{ post.url }}">{{ post.title}}</a></h2>
		<span class="posts-date">{{ post.date | date: "%b %-d, %Y" }}</span>
		<div class="content">{{ post.content }}</div>
	</article>
{% endfor %}
</div>

<div class="aside">
	<h2>Who?</h2>
	<p>Hi, I am Chris; professor, logo designer, UI specialist, and VP design & dev at Sprout Studio.</p>
</div>

<div style="float: left; width: 100%">
	<a id="embed-24871282" href="https://maps.roadtrippers.com/?a2=t!24871282&lat=39.314837072043076&lng=-80.19466978732669&utm_campaign=trip&utm_medium=share&utm_source=embed&z=7.1869070763705345">Walt Disney World Trip on Roadtrippers</a><br><script>!function(d,l,h,w,id){var a = d.getElementById(id);var ifr = d.createElement("iframe");ifr.src = l;ifr.height = h;ifr.width = w; ifr.scrolling = "no"; a.parentNode.insertBefore(ifr, a);a.parentNode.removeChild(a);}(document,"https://maps.roadtrippers.com/embedded/trips/24871282",800,800,"embed-24871282");</script>
</div>

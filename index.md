---
title: Miniblog
---

<ul>
	{% for post in site.posts %}
		{% unless post.isOriginal %}
			<li>
				<a href="{{ post.url }}">{{ post.title }}</a>
			</li>
		{% endunless %}
	{% endfor %}
</ul>

<p>
	<a href="{{ site.url }}/tags.html">List of tags</a>
</p>


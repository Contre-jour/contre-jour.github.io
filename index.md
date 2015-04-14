---
title: Miniblog
googleSiteVerification: _v0CgoEkdDkOm6hQZWuOA8e3OIofyjfSHvvus6iqq-8
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

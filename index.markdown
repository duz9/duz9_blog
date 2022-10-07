---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<ul>
{% for post in site.posts %}
<li>
<h2>{{ post.title }}</h2>
<small>Made by: {{ post.author }}</small>
<p>{{ post.excerpt | strip_html | truncate:15 }}</p>
<a href="{{ site.baseurl }}{{ post.url }}">Read More</a>
<!-- <a href="{{ post.url }}">Read More</a> -->
</li>
<hr>
{% endfor %}
</ul>
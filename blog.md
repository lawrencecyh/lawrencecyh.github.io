---
layout: content
title: Blog
---
{% for post in site.posts %}
<h2> {{ post.title }} </h2>
<p>Published {{ post.date | date_to_string }}</p>
{{ post.excerpt }}

<div class="readmore">
<a href="{{ post.url }}" >read more</a>
</div>

<hr class="divider">
{% endfor %}

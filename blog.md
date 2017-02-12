---
layout: content
title: Blog
---
{% for post in site.posts %}
<div>
<h1> {{ post.title }} </h1>
<p>{{ post.date | date_to_string }}</p>

{{ post.excerpt }}

<div class="readmore">
<a href="{{ post.url }}" >read more</a>
</div>

</div>
<hr class="small"
  align="center"
  style="width: 75%">
{% endfor %}

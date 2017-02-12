---
layout: default
title: Blog
---
{% for post in site.posts %}
<div>
<span style="float:right; padding-top: 5px; max-width: 30%">
    {{ post.date }}
</span>
<h1> {{ post.title }} </h1>

{{ post.excerpt }}

<div class="readmore">
<a href="{{ post.url }}" >read more</a>
</div>

</div>
<hr class="small"
  align="center"
  style="width: 75%">
{% endfor %}

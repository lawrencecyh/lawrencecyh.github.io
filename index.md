---
layout: content
---
{% for post in site.posts %}

<div class="excerpt" onclick="location.href='{{post.url}}';">

{{ post.date | date_to_string }}

<h2>{{ post.title }}</h2>

<p>{{ post.excerpt }}</p>
</div>

{% endfor %}

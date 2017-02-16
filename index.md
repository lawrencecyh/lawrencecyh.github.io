---
layout: default
---
{% for post in site.posts %}

<div class="excerpt" onclick="location.href='{{post.url}}';">

<h2>{{ post.title }}</h2>

{{ post.date | date_to_string }}

<p>{{ post.excerpt }}</p>
</div>

{% endfor %}

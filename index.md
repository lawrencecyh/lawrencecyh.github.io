---
layout: default
header-background: /res/pano.jpg
---

{% for post in site.posts %}

<div class="excerpt" onclick="location.href='{{post.url}}';">

<p class="datestring">
{{ post.date | date_to_string }}
</p>

<h2>{{ post.title }}</h2>

<p>{{ post.excerpt }}</p>
</div>

{% endfor %}
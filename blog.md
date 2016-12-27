---
layout: default
title: Blog
---
<div class="page-div">
    {% for post in site.posts %}
        <div>
        <span style="float:right; padding-top: 5px; max-width: 30%">
            {{ post.date }}
        </span>
        <h1> {{ post.title }} </h1>

        {{ post }}

        </div>
        <hr class="small"
          align="center"
          style="width: 75%">
    {% endfor %}
</div>

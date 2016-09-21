---
layout: archive
title: Archive
permalink: /archive/
---

<div class="posts">
  {% for post in site.posts%}
    <article class="post">
      <div class="container">
        <div class="date">
          {{ post.date | date: "%B %e, %Y" }}
        </div>
        <h1><a href="{{ site.baseurl }}{{post.url}}">{{ post.title}}</a></h1>
      </div>
    </article>
  {% endfor %}
</div>

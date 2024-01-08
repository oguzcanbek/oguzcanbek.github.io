---
layout: page
permalink: /oyku/
---

<div class="oykus">
  {% for post in site.categories.oyku %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Okumaya devam et</a>

    </article>
  {% endfor %}
</div>

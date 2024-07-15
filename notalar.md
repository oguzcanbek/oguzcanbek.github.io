---
layout: page
permalink: /notalar/
---


<ul>
<li><a href="https://oguzcanbek.github.io/notes/Op_6_Gazel_No_2.pdf"> Gazel, Op. 6, No. 2</a></li>
<li><a href="https://oguzcanbek.github.io/notes/Op_6_Gazel_No_3.pdf"> Gazel, Op. 6, No. 3</a></li>
<li><a href="https://oguzcanbek.github.io/notes/Op_15_No_1_Raks.pdf"> Raks,  Op. 15, No. 1</a></li>
</ul>

<div class="oykus">
  {% for post in site.categories.notalar %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Okumaya devam et</a>

    </article>
  {% endfor %}
</div>

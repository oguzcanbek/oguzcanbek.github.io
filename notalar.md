---
layout: page
permalink: /notalar/
---

<!-- <a href="{{ site.baseurl }}/notalar/2024_05_21-Op_13_No_2_Gazel.pdf">  Gazel, Op. 13, No. 2</a> -->

<ul>
<li><a href="https://github.com/oguzcanbek/oguzcanbek.github.io/blob/master/notalar/_posts/2024_05_21-Op_13_No_2_Gazel.pdf"> Gazel, Op. 13, No. 2</a></li>
<li><a href="https://github.com/oguzcanbek/oguzcanbek.github.io/blob/master/notalar/_posts/2024_05_22-Op_15_No_1_Raks.pdf">  Raks,  Op. 15, No. 1</a></li>
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

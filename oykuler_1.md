---
layout: page
permalink: /oykuler_1/
---

<p class="icindekiler" ><b>İçindekiler</b></p> 

<div>
    <ol>
      <li><a href="{{ site.baseurl }}/daire">     Daire</a></li>
      <li><a href="{{ site.baseurl }}/dilenci">   Dilenci</a></li>
      <li><a href="{{ site.baseurl }}/duzeltme">  Düzeltme</a></li>
      <li><a href="{{ site.baseurl }}/ilk_fasil"> İlk Fasıl</a></li>
      <li><a href="{{ site.baseurl }}/365">       365 Numaralı Daire</a></li>
      <li><a href="{{ site.baseurl }}/kedi">      Kayıp Kedi Aranıyor!</a></li>
      <li><a href="{{ site.baseurl }}/son_fasil"> Son Fasıl</a></li>
    </ol>
</div>


<div class="oykus">

  {% for post in site.categories.oykuler_1 %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Okumaya devam et</a>

    </article>
  {% endfor %}
</div>


<style>
    p{
        color: black;
    }
        font-size:  48px;
    .icindekiler {
        font-size:  96px;
        text-align: center;
    }
    .paragraph2 {
        font-size:   20px;
        text-align:  center;
    }
    .paragraph3 {
        font-size:   20px;
        text-align:  right;
        font-weight: bold
    }
    .paragraph4 {
        font-size:   20px;
        text-align:  left;
        font-weight: bold
    }
    span {
        font-size:   20px;
        font-weight: bold;
        font-family: 'Franklin Gothic Medium'
    }  
    span2 {
        font-size:   20px;
        font-weight: bold;
        font-family: 'Bahnschrift'
    }
</style>
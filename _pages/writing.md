---
permalink: /writing/
layout: archive
title: "Writing"
excerpt: "About me"
author_profile: true
---

{% include base_path %}

<div class="list">
  <div class="list__item">
    <a href="https://chaichronicles.beehiiv.com/" class="archive__item-link">
      <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
        <h2 class="archive__item-title" itemprop="headline">Chai Chronicles</h2>
        <p class="archive__item-excerpt" itemprop="description">I started an irregular email newsletter and then went AWOL for a little less than a year. I regretted it. I am restarting it. I designed this to be a medium for digitally staying in touch with friends and family. I intended it be unstructured and mostly consists of my weekly learnings. </p>
      </article>
    </a>
  </div>
</div>

<hr>

{% for post in site.posts %}
  {% include archive-single-post.html %}
{% endfor %}


<!-- <ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ base_path }}{{ post.url }}" class="archive__item-link">
            <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
                <h2 class="archive__item-title" itemprop="headline">{{ post.title }}</h2>
                <p class="archive__item-excerpt" itemprop="description">{{ post.excerpt }}</p>
            </article>
        </a>
    </li>
  {% endfor %}
</ul> -->
<!--
<div class="list">
  <div class="list__item">
    <a href="https://chaichronicles.beehiiv.com/" class="archive__item-link">
      <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
        <h2 class="archive__item-title" itemprop="headline">Chai Chronicles</h2>
        <p class="archive__item-excerpt" itemprop="description">I started an irregular email newsletter and then went AWOL for a little less than a year. I regretted it. I am restarting it.</p>
      </article>
    </a>
  </div>
  Add more grid items here
</div>
-->

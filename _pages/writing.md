---
permalink: /writing/
title: "Writing"
excerpt: "About me"
author_profile: true
---

{% include base_path %}


<ul>
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
</ul>

<!-- <div class="list">
  <div class="list__item">
    <a href="https://chaichronicles.beehiiv.com/" class="archive__item-link">
      <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
        <h2 class="archive__item-title" itemprop="headline">Chai Chronicles</h2>
        <p class="archive__item-excerpt" itemprop="description">I started an irregular email newsletter and then went AWOL for a little less than a year. I regretted it. I am restarting it.</p>
      </article>
    </a>
  </div>
  <!-- Add more grid items here -->
<!-- </div> -->
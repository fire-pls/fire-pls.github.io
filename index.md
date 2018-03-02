---
layout: landing
title: top
---

<div id="content">
  <div class="landing">

    <div class="landing-msg">
      <h1>trevor malard</h1>
      <p>digital creative</p>
      {% assign landing_links = site.links %}

      {% for link in landing_links %}
        <br><div class="landing-link" id="{{link}}"><p>{{ link | remove: "/" }}</p></div>
      {% endfor %}
    </div>

  </div>
</div>

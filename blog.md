---
title: Design Office Blog
permalink: /blog/
layout: page
---
<style type="text/css">
  h2 a {text-decoration: none;}
</style>
<div class="usa-width-three-fourths usa-layout-docs-main_content">

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <h5>{{ post.author }}</h5>
  <p>{{ post.excerpt }} <a href="{{ post.url }}">read more</a>
  </p>
{% endfor %}

</div>

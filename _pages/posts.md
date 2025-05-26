---
layout: page
title: Posts
permalink: /posts/
---

# Latest Posts & Updates

{% if site.posts.size > 0 %}

<div class="post-list">
  {% for post in site.posts %}
  <article class="post-item">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
    {% if post.excerpt %}
    <div class="post-excerpt">{{ post.excerpt }}</div>
    {% endif %}
    <p><a href="{{ post.url | relative_url }}">Read more →</a></p>
  </article>
  {% unless forloop.last %}<hr>{% endunless %}
  {% endfor %}
</div>
{% else %}
<p>Posts coming soon! I'll be sharing insights about software engineering, scientific computing, renewable energy technology, and the intersection of science and software development.</p>

<p>Topics you can expect:</p>
<ul>
  <li>Building scalable applications for scientific workflows</li>
  <li>Machine learning for materials discovery</li>
  <li>Energy modeling and simulation tools</li>
  <li>Transitioning from academia to tech industry</li>
  <li>Full-stack development best practices</li>
</ul>

<p>Subscribe to the <a href="{{ '/feed.xml' | relative_url }}">RSS feed</a> to stay updated!</p>
{% endif %}

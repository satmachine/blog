---
layout: default
title: Home
---
<section class="home-intro">
  <h2>Engineering excellence, delivered.</h2>
  <p>
    Welcome to the SATM Engineering Blog. We share stories from the field, deep dives into
    the systems we build, and the lessons that help our partners move faster with confidence.
  </p>
</section>
<section class="post-list">
  {% if site.posts.size > 0 %}
    {% for post in site.posts %}
    <article>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p class="post-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
        {% if post.categories %}
        • {{ post.categories | join: ', ' }}
        {% endif %}
      </p>
      <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
      <a class="read-more" href="{{ post.url | relative_url }}">Read more →</a>
    </article>
    {% endfor %}
  {% else %}
    <p>New content is on the way. Check back soon for fresh updates from the SATM Engineering team.</p>
  {% endif %}
</section>

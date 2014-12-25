---
layout: page
title: Blog Home
tagline: "Just a Jekyll Blog"
---
{% include JB/setup %}

This is my new Jekyll blog hosted on [GitHub](https://github.com/)!

<ul class="list-group">
  {% for post in site.posts limit:15 %}
  <li class="list-group-item">
    <article>
      <a href="{{ site.url }}{{ post.url }}">
        {{ post.title }}
        <span class="date pull-right">
          <time datetime="{{ post.date | date_to_xmlschema }}">
            {{ post.date | date: "%B %d, %Y" }}
          </time>
        </span>
      </a>
    </article>
  </li>
  {% endfor %}
</ul>

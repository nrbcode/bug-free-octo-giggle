---
title: Author
layout: page
permalink: /author/
---
The _frontmatter_ title not necessary on this page because it is written in html.
<h1>Contacts page</h1>
<p>{{ page.date | date_to_string }}<p>
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
The _frontmatter_ title not necessary on this page because it is written in html.
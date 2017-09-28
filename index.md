---
layout: default
---
<section>
<h1>Posts</h1>

<ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

{% if site.github.is_project_page %}
  <p class="view"><a href="{{ site.github.repository_url }}">Projects on GitHub <small>{{ github_name }}</small></a></p>
{% endif %}

</section>

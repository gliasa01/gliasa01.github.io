---
layout: default
---
<section>
<h1>Learn</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{{ content }}

{% if site.github.is_project_page %}
  <p class="view"><a href="{{ site.github.repository_url }}">Projects on GitHub <small>{{ github_name }}</small></a></p>
{% endif %}

</section>

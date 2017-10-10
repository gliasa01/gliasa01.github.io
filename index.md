---
layout: default
---
<section>
<h1>Posts</h1>

<ul class="posts">
    {% for post in site.posts %}
      <li>{{ post.date | date_to_string }} &raquo;&raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<h1>Files</h1>  
  <ul>Learn Linux, 101: The Linux command line &raquo;&raquo; <a href="https://www.ibm.com/developerworks/linux/library/l-lpic1-103-1/l-lpic1-103-1-pdf.pdf">[PDF]</a></ul>
  <ul>Learn Linux, 101 : Hard disk layout &raquo;&raquo; <a href="https://www.ibm.com/developerworks/library/l-lpic1-102-1/l-lpic1-102-1-pdf.pdf">[PDF]</a></ul>
  <ul>Learn Linux, 101: File and directory management &raquo;&raquo; <a href="https://www.ibm.com/developerworks/linux/library/l-lpic1-103-3/l-lpic1-103-3-pdf.pdf">[PDF]</a></ul>

<h1>Downloads</h1>
  <ul>VisuaLG &raquo;&raquo; <a href="https://sourceforge.net/projects/visualg30/">Download</a></ul>
  <ul>Python &raquo;&raquo; <a href="https://www.python.org/downloads/">Download</a></ul>
  <ul>PyCharm Edu &raquo;&raquo; <a href="https://www.jetbrains.com/pycharm-edu/download">Download</a></ul>
  <ul>Scratch &raquo;&raquo; <a href="https://scratch.mit.edu/">Download</a></ul>
  <ul>Arduino &raquo;&raquo; <a href="https://www.arduino.cc/en/Main/Software">Download</a></ul>

{% if site.github.is_project_page %}
  <h1>Projects</h1>
  <p class="view"><a href="{{ site.github.repository_url }}">Projects on GitHub <small>{{ github_name }}</small></a></p>
{% endif %}

</section>

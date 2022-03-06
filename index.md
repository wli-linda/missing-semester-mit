My lecture notes and completed exercises from [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/).
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
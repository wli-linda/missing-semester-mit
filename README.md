Exercises from [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/).

### Lecture Notes and Exercises
Here are my lecture notes and completed exercises:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

  <h3>Hyde</h3>
  <ul>
    {% for post in site.categories.hyde %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>


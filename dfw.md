
  <h3>Hyde</h3>
  <ul>
    {% for post in site.categories.hyde %}
  <hr />
  <div class="row">
    <div class="span2">
    {% if post.thumbnail %}
	    <img src="{{ post.thumbnail }}" align="center" />
	  {% else %}
	    <img src="/assets/img/no-thumbnail.png" align="center" />
	  {% endif %}
    </div>
    <div class="span10">
      <p><h3><a href="{{ post.url }}">{{ post.title }}</a></h3></p>
      <p>
        {{ post.excerpt }}
    </p>
  </div>
  </div>
    {% endfor %}
  </ul>



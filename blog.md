
  {% for post in site.posts %}
 
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
  <hr />
  {% endfor %}

<div id="amzn-assoc-ad-1254b9fb-510c-478e-b347-8ee7479ccaf8"></div><script async src="//z-na.amazon-adsystem.com/widgets/onejs?MarketPlace=US&adInstanceId=1254b9fb-510c-478e-b347-8ee7479ccaf8"></script>


<ul>
  {% for post in site.posts %}
    <p>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ page.author | default: site.author }}</small>
      {{ post.excerpt }}
    </p>
  {% endfor %}
</ul>


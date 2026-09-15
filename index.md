Hihi! Welcome to my Blog, I'm Anastasia
 c:

 # My Posts:

 <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
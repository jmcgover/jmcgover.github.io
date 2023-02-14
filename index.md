This is a test homepage.

<h1>Posts</h1>
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%Y/%m/%d"}} <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


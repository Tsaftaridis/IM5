# IM5

Auth IM questions, 5th edition

<ul>
  {% for post in _posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

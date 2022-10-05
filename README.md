# IM5

Auth IM questions, 5th edition

{% for post in site.posts %}
    <!-- link to each post in index.html -->
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

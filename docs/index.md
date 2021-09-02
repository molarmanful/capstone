# NYU Abu Dhabi Interactive Media Capstone 2021-2022
## Benjamin Pang

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/capstone{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

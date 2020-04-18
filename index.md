# A blog about programming

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

| | | 
|-| - |
| [Building the OpenJDK](openjdk.html) | 2020-04-18 |

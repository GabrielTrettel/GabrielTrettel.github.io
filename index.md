
Personal website to store my things


<ul>
  {% for recipe in site.recipes %}
    <li><a href="{{ recipe.url }}">{{ recipe.title }}</a></li>
  {% endfor %}
</ul>
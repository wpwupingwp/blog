## Hello world
Blog built with Github Pages.
## Test
Code
```python
from random import randint
for i in range(6):
  print(randint(1, 7))
```
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

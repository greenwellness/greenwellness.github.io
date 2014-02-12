---
published: false
---


## Configuratie

In `_config.yml` staan algemene instellingen van de site.

## Sjablonen

Deze site (Jekyll) maakt gebruik van zgn. `Liquid` templates (sjablonen). Deze zien er ongeveer als volgt uit:

```html
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
```


Deze site is gemaakt met behulp van o.a. Jekyll. Documentatie van de componenten kun je hieronder vinden:

* [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
* [Jekyll Bootstrap](http://jekyllbootstrap.com)
* [Jekyll Bootstrap themes](http://github.com/plusjade/jekyllbootstrap)
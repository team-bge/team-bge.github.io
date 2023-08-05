---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Tutorials
<ul>
{% for tutorial in site.tutorials %}
    <li><a href="{{ tutorial.url }}">{{ tutorial.title }}</a></li>
{% endfor %}
</ul>

# API Reference
<ul>
<li><a href="https://team-bge.github.io/bge-core/">bge-core</a></li>
</ul>

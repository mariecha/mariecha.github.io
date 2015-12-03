---

layout: default

---

Texte qui apparait dans content

Voilà ma fameuse page, suivie de mes articles...

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
	    </li>
  {% endfor %}
</ul>

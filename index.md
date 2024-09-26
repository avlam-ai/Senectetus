# Writings of Seneca and Epictetus
Essays on reflections on the writings of the likes of Seneca and Epictetus, and how we can apply such wisdom to everyday life

<h1>{{ page.title }}</h1>

{% for post in site.posts %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<p>{{ post.excerpt }}</p>
{% endfor %}


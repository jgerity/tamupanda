---
layout: default
---

{% for post in site.posts %}
<div>
<a href="{{post.url}}"><h1 style="margin-bottom: -10px;">{{post.title}}</h1></a>
<span title="{{post.date}}">{{ post.date | date: "%B %-d %Y" }}</span>
{{post.content}}

<hr />
</div>
{% endfor %}

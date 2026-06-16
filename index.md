---
layout: default
title: Home
---

## Hi, I'm Archit

This is an open canvas for my thoughts and stories. 

If you're here then you already know what you're looking for :'). Have Fun. 

Reach me at [{{ site.author.email }}](mailto:{{ site.author.email }}).

---

### Blogs

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — <span class="post-date">{{ post.date | date_to_string }}</span>
{% endfor %}

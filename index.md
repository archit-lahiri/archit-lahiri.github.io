---
layout: default
title: Home
---

# Hi, I'm Archit

I write about my thoughts and stories. This is an open canvas for ideas
I'm thinking through — feel free to look around.

Reach me at [{{ site.author.email }}](mailto:{{ site.author.email }}).

---

## Blogs

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — <span class="post-date">{{ post.date | date_to_string }}</span>
{% endfor %}

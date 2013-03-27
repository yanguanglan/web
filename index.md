---
layout: page
resume: 1
---
<div class="index-artical">
    <ul class="index-left">
    {% for post in site.categories.blog limit:5 %}
        <li>
            <h2>
            	<a href="{{ post.url }}">{{ post.title }}</a>
            </h2>
            <span class="title-desc">{{ post.description }}</span>
        </li>
    {% endfor %}
    </ul>
    <div>(<a href="{{ site.production_url }}/archive.html">more articles</a>)</div>
</div>
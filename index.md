---
layout: page
---
<div class="index-artical">
    <ul class="index-left">
    {% for post in site.categories.blog %}
        <li>
            <h2>
            	<a href="{{ post.url }}">{{ post.title }}</a>
            </h2>
            <span class="title-desc">{{ post.description }}</span>
        </li>
    {% endfor %}
    </ul>
</div>
---
layout: default
---

<article id="post">
    <header class="post-header">
        <h1 class="post-title">{{ page.title }}</h1>
        <div class="post-date">{{ page.date | date: "%b %-d, %Y" }}</div>
    </header>
    {{ content }}
</article>

<center><a href="/blog">Back to other posts</a></center>

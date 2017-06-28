---
title: Blog
description: Welcome to the Silver Strand Therapy blog. We have tons of great physical
  therapy resources to help you on your road to recovery, fitness, and optimal health.
layout: page
---

Welcome to the [Silver Strand Physical Therapy](/) blog! Check out some of our recent posts below:

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

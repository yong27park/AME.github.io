---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
header:
  og_image: "/images/Home_3.png"
---

<style>
  .news-list {
    list-style: none;
    padding-left: 0;
    margin-top: 1.5rem;
  }
  .news-item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 1.2rem;
    padding-bottom: 1rem;
    border-bottom: 1px solid #f2f2f2;
  }
  .news-date {
    background-color: #2b2b2b;
    color: #ffffff;
    font-size: 0.8rem;
    font-weight: 600;
    padding: 0.25rem 0.6rem;
    border-radius: 4px;
    white-space: nowrap;
    margin-right: 1rem;
    margin-top: 0.2rem;
  }
  .news-content {
    flex: 1;
  }
  .news-title {
    font-size: 1.05rem;
    font-weight: bold;
    margin: 0 0 0.3rem 0;
  }
  .news-title a {
    color: #111;
    text-decoration: none;
  }
  .news-title a:hover {
    text-decoration: underline;
  }
  .news-excerpt {
    font-size: 0.9rem;
    color: #555;
    margin: 0;
    line-height: 1.4;
  }
</style>

About Us - Atelier of Microelectronics (AME)
===
<p align="center">
  <img src="{{ site.baseurl }}/images/Home_3.png" width="600">
</p>
 Historically, from the Renaissance through the 19th century, the 'Atelier' was a pure place where master craftsmanship met youthful innovation to redefine art and technology. Inspired by this legacy, the Atelier of Microelectronics (AME) pusues to be dedicated to advancing analog and mixed-signal IC design. Through hands-on experimentation, rigorous circuit synthesis, and collaborative learning, we aim to develop next-generation microelectronic solutions. 

Our Mission
===
Our mission at the Atelier of Microelectronics (AME) is as follows:

1. Research circuits and systems that benefit humanity.
2. Identify fundamental problems and solve them by focusing on key insights.
3. Grow together through open exploration and close collaboration.

Recent News
===

<ul class="news-list">
  {% for post in site.posts limit:5 %}
    <li class="news-item">
      <span class="news-date">{{ post.date | date: "%b %d, %Y" }}</span>
      <div class="news-content">
        <div class="news-title">
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </div>
        <div class="news-excerpt">
          {% if post.excerpt %}
            {{ post.excerpt | strip_html | truncatewords: 25 }}
          {% else %}
            {{ post.content | strip_html | truncatewords: 25 }}
          {% endif %}
        </div>
      </div>
    </li>
  {% endfor %}
</ul>


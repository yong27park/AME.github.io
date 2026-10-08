---
title: "New & Announcements"
permalink: /news/
author_profile: true
---

<style>
  /* 뉴스 목록의 제목 링크를 검정색으로 지정 */
  .archive__item-title a {
    color: #111111 !important;
    text-decoration: none;
  }
  /* 마우스를 올렸을 때 강조 효과 */
  .archive__item-title a:hover {
    color: #555555 !important;
    text-decoration: underline;
  }
</style>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

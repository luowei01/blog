---
layout: page
title: 全部文章
permalink: /book/
---

<style>
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #f0f0f0;
  }

  .navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
  }

  .navbar ul li {
    display: inline;
  }
</style>

<div class="navbar">
  <ul>
    {% for item in page.navigation %}
      <li><a href="{{ item.url }}">{{ item.name }}</a></li>
    {% endfor %}
  </ul>
</div>

<iframe src="https://luowei01.github.io/blogs" style="width: 100%; height: calc(100vh - 80px); border: none;"></iframe>

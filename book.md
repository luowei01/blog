---
layout: default_without_nav
permalink: /book/
---
<style>
  .navbar {
    display: flex;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    z-index: 1000; /* 确保导航栏位于其他内容上方 */
    justify-content: space-around;
    align-items: center;
    padding: 5px;
    background-color: #f0f0f0;
    font-size: 18px; /* 放大字号 */
  }

  .navbar a {
    text-decoration: none;
    color: #333;
  }
  .current {
    font-weight: bold;
    color: #ff0000; /* 高亮颜色 */
  }
</style>
<div class="navbar">
  <a href="{{ site.baseurl }}/">首页</a>
  <a href="{{ site.baseurl }}/about/">关于</a>
  <a href="{{ site.baseurl }}/archive/">归档</a>
  <a href="{{ site.baseurl }}/tags/">标签</a>
  <a href="{{ site.baseurl }}/book/" class="current">全部博客</a>
</div>
<iframe src="https://luowei01.github.io/blogs" style="width: 100%; height: calc(100vh - 40px); border: none;margin-top: 40px;"></iframe>
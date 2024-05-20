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
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* 添加阴影以提升视觉效果 */
  }

  .navbar a {
    text-decoration: none;
    color: #333;
  }
  .current {
    font-weight: bold;
    color: #ff0000; /* 高亮颜色 */
  }
    /* 空白占位元素 */
  .navbar-placeholder {
    height: 40px;
    /* 与导航栏高度相同 */
  }
  @media (max-width: 600px) {
  .navbar {
    flex-direction: column; /* 将导航栏改为列方向排列 */
    align-items: flex-start; /* 左对齐 */
    padding: 10px; /* 增加内边距 */
    height: auto; /* 自适应高度 */
  }
  .navbar a {
    padding: 10px 0; /* 增加链接之间的间距 */
  }
  .navbar-placeholder {
    height: auto; /* 让占位元素自适应高度 */
  }
  iframe {
    height: calc(100vh - var(--navbar-height)); /* 使用CSS变量动态设置高度 */
  }
  }
</style>
<div class="navbar">
  <a href="{{ site.baseurl }}/">首页</a>
  <a href="{{ site.baseurl }}/about/">关于</a>
  <a href="{{ site.baseurl }}/archive/">归档</a>
  <a href="{{ site.baseurl }}/tags/">标签</a>
  <a href="{{ site.baseurl }}/book/" class="current">全部博客</a>
</div>
<div class="navbar-placeholder"></div>
<iframe src="https://luowei01.github.io/blogs" style="width: 100%; height: calc(100vh - 40px); border: none;margin-top: 40px;"></iframe>
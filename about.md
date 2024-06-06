---
layout: default_without_nav
permalink: /about/
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
  <a href="{{ site.baseurl }}/about/" class="current">关于</a>
  <a href="{{ site.baseurl }}/archive/">归档</a>
  <a href="{{ site.baseurl }}/tags/">标签</a>
  <a href="https://blog.chateda.top/" >全部博客</a>
</div>
<style>
  /* 空白占位元素 */
  .navbar-placeholder {
    height: 40px; /* 与导航栏高度相同 */
  }
</style>
<div class="navbar-placeholder"></div>
## 关于我
你好，我是luowei,一名在读研究生，研究PCB设计自动化。

[CSDN](https://blog.csdn.net/weixin_45728532?type=blog)。

[个人技术公众号](https://blog.csdn.net/weixin_45728532?type=blog)分享编程学习路线、编程学习资源，记录技术成长，欢迎扫码添加：

![公众号二维码](https://cdn.jsdelivr.net/gh/luowei01/images/images/blog.png)



## 版权声明

博客文章是我原创文章，版权归我所有，转载请与我联系获得授权许可。

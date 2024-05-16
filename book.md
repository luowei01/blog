<style>
  .navbar {
    display: flex;
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
</style>

<div class="navbar">
  <a href="{{ site.baseurl }}/">首页</a>
  <a href="{{ site.baseurl }}/about/">关于</a>
  <a href="{{ site.baseurl }}/archive/">归档</a>
  <a href="{{ site.baseurl }}/tags/">标签</a>
  <a href="{{ site.baseurl }}/book/">全部博客</a>
</div>

<iframe src="https://luowei01.github.io/blogs" style="width: 100%; height: calc(100vh - 80px); border: none;"></iframe>
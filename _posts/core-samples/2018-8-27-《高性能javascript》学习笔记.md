# 《高性能javascript》学习笔记  

1)由于脚本会阻塞页面其它资源的下载，因此推荐将所有的<script>标签尽可能放到<body>标签的底部，以尽量减少对整个页面下载的影响。

2）减少外链的JS,CSS等的http请求

3）<script defer > defer:延迟加载  。defer中的脚本在window.onload执行之前。
  
4）一个标识符所在的位置越深，它的读写速度也就越慢。因此函数中读写局部变量总是最快的，而读写全局变量通常是最慢的。

5）小心使用闭包

6）减少DOM的访问与修改

7）element.cloneNode 替代 document.createElement

8)querySelectorAll()的使用

9）减少重绘repaints 重排 reflows

10) 让动画元素脱离文档流

11）使用事件委托来减少事件处理器的数量

12）正则减少回溯

13）预加载，JAVASCRIPT压缩合并，使用缓存

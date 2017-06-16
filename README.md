# ZOOM.JS

一个用于图像缩放的简单jQuery插件; as seen on Medium.

## How
1. 将zoom.js和zoom.css文件链接到您的网站或应用程序。

  ```html
  <script src="js/transition.js"></script>
  ```
2. zoom.js依赖于Bootstrap中的transition.js文件，因此请确保包含该文件。
  
  ```html
  <link href="css/zoom.css" rel="stylesheet">
  <script src="dist/zoom.js"></script>
  ```

3. data-action="zoom"向要缩放的图像添加属性。例如：

  ```html
  <img src="img/blog_post_featured.png" data-action="zoom">
  ```

## where
在理论上，zoom.js应该在浏览器（ie9+）中运行。



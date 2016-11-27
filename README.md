# highlighting
语法高亮插件
是加入 js 和 css 代码渲染。


渲染高亮

进入 `/themes/xxx`(你的主题) 执行：

```bash
git clone https://github.com/bsed/highlighting.git
```
将会下载 .js 和 .css 两个渲染脚本，然后编辑 `header.jsp`，在如下位置插入如下代码：
```html
<link rel="stylesheet" href="./prism.css">
<script src=".prism.js"></script>
```

如图：
![prism](https://raw.githubusercontent.com/bsed/images/master/2016/11/prism-js-css.png)
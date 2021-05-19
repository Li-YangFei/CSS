# CSS

## CSS 基础与选择器初识

1. css加载有几种方式？
   1. 外部样式
      1. `<link rel="stylesheet" href="style.css">`
      2. `@import url();`
   2. 内部样式`<style></style>`
   3. 嵌入样式(不推荐)`<div style="..."></div>`
2. `link`和`@import`区别
   1. `link`是`XHTML`标签，可以加载`CSS`也可以定义`RSS`,`@import`只能用于加载`CSS`
   2. `link`页面加载时同时加载(并行加载)，`@import`页面加载完成后加载
   3. `link`兼容性更强
3. CSS选择器常见的几种
   1. 基础`id、class、tag、*`
   2. 属性选择器
   3. 组合选择器
      1. 多元素选择器
      2. 后代选择器
      3. 子元素选择器
      4. 直接相邻选择器
      5. 普通相邻选择器
   4. 伪类选择器
      1. UI元素伪类选择器
      2. 结构伪类选择器
4. `src`和`href`的区别
   1. `href`时超文本引用，建立文档和元素之间的连接，常用有：`link、a`
   2. `src`时`source`资源的缩写，是页面不可缺少的一部分，`src`指向的内容会被嵌入文档指定的位置，常用有：`img、script、iframe`
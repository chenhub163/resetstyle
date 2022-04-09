# CSS重置样式表

`resetstyle`是一个轻量的css样式表，主要负责重置掉浏览器的默认样式。

它不依赖与任何的第三方包，就纯css文件

目前`resetstyle`能够帮助你重置掉哪些元素？

- 根元素: 完成
- 元数据脚本: 完成
- 文本级别元素: 完成
- 分组内容: 完成
- 文档块: 完成
- 互动元素: 完成
- 嵌入内容元素: 完成
- 表格元素: 未完成 
- 表单元素: 未完成

由于嵌入内容元素，表格元素，表单元素的应用场景比较负责，暂时未进行大幅度的调整，不过这些元素都会在后续的维护中进行。

> 目前html元素总共有：135个元素，已废弃了28个元素，因此可使用的元素总共有107个，但是常用的就没几个了。
> `resetstyle`是基于107个元素数量来进行样式重置的。
> 
> 元素数量参考自：[mdn](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
> 元素分类参考自：[HTML5元素周期表](https://www.xuanfengge.com/funny/html5/element)

## 安装

```shell
npm install resetstyle
yarn add resetstyle
```

## 使用

```js
import "resetstyle"
```
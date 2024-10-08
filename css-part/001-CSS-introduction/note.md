# CSS 介绍

CSS（Cascading Style Sheets，层叠样式表）是一种用来表现 HTML 或 XML 文档样式的语言。CSS 用来控制网页的布局、字体、颜色、背景、边框等。CSS3 则是对 CSS 的升级，加入了更多的功能，使得 CSS 更加强大和灵活。

使用CSS的目的就是为网页添加美观的界面。

## 语法

CSS规则由两个主要部分构成：选择器以及一条或多条声明。

- 选择器：选择器是您需要改变样式的HTML元素
- 声明：声明有多条，每条声明都包含一个属性和一个值
    - 属性：属性是您希望应用于HTML元素的样式属性
    - 值：值是属性的具体设置值
    - 属性和值之间用冒号分隔
    - 多条属性和值之间用分号分隔

```html
<style>
  /* 选择器 */
  h1 {
    /* 声明 */
    color: red;
    font-size: 24px;
  }
</style>
```
# HTML5简介与基础骨架

## HTML5简介

超文本标记语言

- 双标签，如`<html></html>`
- 单标签，如`<img>`

## HTML5的DCOCTYPE声明

```html
<!DOCTYPE html>
```

避免浏览器的怪异模式（在不同的浏览器上效果不一致）。

## 基本骨架

`html`

下设

- `head`
- `body`

```html
<!-- 声明 -->
<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

</body>

</html>
```

`html`限定了文档的开始和结束。

`head`的内容不会呈现给用户。

`body`的内容会呈现给用户。

```html
<!-- 声明 -->
<!DOCTYPE html>

<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    用户会看到。
</body>

</html>
```

### `title`标签

`<title>`是`<head>`标签中唯一必须要求包含的东西，如果写`head`，呢么一定要写`title`。`<title>`有利于SEO（搜索引擎优化）。

### `meta`标签

`<meta>`是一个单标签，用来设定一些属性。

```html
<meta charset="UTF-8">
```

使用UTF-8编码格式，以适配世界上的绝大多数语言文字。

注意：`<!DOCTYPE html>`是声明，不是基本骨架中的标签。
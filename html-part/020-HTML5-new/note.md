# HTML5新增标签——New HTML5 Tags

HTML5出现之前，我们主要采用`<div>`+CSS来布局我们的页面。这样的布局方式使得HTML文档不够清晰。为了解决上述的缺点，HTML5新加入了一些语义标签。

`<div>`是容器，是目前页面中见到最多的标签。

## 新标签

```html
<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>笔记</title>
</head>

<body>
    <header>Header</header>
    <nav>Navigation</nav>
    <article>Article
        <section>Section 1</section>
        <section>Section 2</section>
    </article>
    <aside>Aside</aside>
    <footer>Footer</footer>
</body>

</html>
```
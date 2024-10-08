### 选择题
**1. 在HTML中，哪个标签用于定义文档的主标题？**
   - A. `<h1>`
   - B. `<title>`
   - C. `<header>`
   - D. `<main>`

我的答案：A

**答案：** A. `<h1>`

**解析：** `<h1>` 标签用于定义文档的主标题。`<title>` 标签用于定义网页的标题（在浏览器标签上显示），`<header>` 标签用于定义页面的头部区域，而 `<main>` 标签用于定义文档的主要内容区域。

---

### 判断题
**2. `<h6>` 标签用于定义文档中的最重要的标题。**
   - 对
   - 错


我：错

**答案：** 错

**解析：** `<h6>` 标签用于定义文档中的最小标题。标题标签从 `<h1>` 到 `<h6>` 逐级递减，`<h1>` 是最重要的标题，`<h6>` 是最不重要的。

---

### 概念辨析
**3. 解释 `<h1>` 和 `<title>` 标签的区别。**

我：`<h1>`是网页内容上的最高级标题，写在`<body>`中，而`<title>`是标签页显示的内容以及收藏夹默认的内容，写在`<head>`中。

**答案：**

- `<h1>` 标签用于定义网页中的主标题，它通常在网页内容的主体部分出现。浏览器会将其显示为大号字体，并且在页面中作为最重要的标题使用。

- `<title>` 标签定义网页的标题，这个标题会显示在浏览器的标签栏或窗口标题中。它不在网页的内容部分显示，而是影响浏览器标签上的文字。

**解析：** `<h1>` 是HTML文档中内容的一部分，用于结构化文本，而 `<title>` 是HTML文档的元数据，用于标识和描述网页。

---

### 实践性编程题
**4. 编写一段HTML代码，创建一个包含主标题、副标题和小节标题的页面。要求使用所有六级标题标签，并说明如何组织这些标题。**

我：

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>标题练习</title>
</head>

<body>
    <h1>主标题</h1>
    <h2>副标题</h2>
    <h3>小节标题</h3>
    <h4>再小一级</h4>
    <h5>再小一级</h5>
    <h6>最小的一级标题</h6>
</body>

</html>
```

**示例代码：**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>标题示例</title>
</head>
<body>
    <h1>主标题</h1>
    <h2>副标题</h2>
    <h3>小节标题 1</h3>
    <h4>子小节标题 1.1</h4>
    <h5>子小节标题 1.1.1</h5>
    <h6>子小节标题 1.1.1.1</h6>
</body>
</html>
```

**解析：** 在这个示例中，我们使用了所有六级标题标签来展示不同层级的标题。`<h1>` 是主标题，最重要的标题；`<h2>` 是副标题，次重要的标题，以此类推。标题的层级关系帮助组织和结构化网页内容，使内容更加清晰易读。

希望这些题目对你理解标题标签的用法有所帮助！

学到了什么：标题中可以加入数字和点，来使层级结构更加清晰。
# 标题

## 标题的介绍与应用

HTML 提供了六种级别的标题标签，从 `<h1>` 到 `<h6>`。这些标签分别用于表示文档中不同级别的重要性， `<h1>` 为最高级别， `<h6>` 为最低级别。

HTML provides six levels of heading tags, from `<h1>` to `<h6>`. These tags represent different levels of importance in a document, with `<h1>` being the highest level and `<h6>` being the lowest.

确保标题仅用于标题，不要为了生成粗体或者大号的文本而使用标题标签。正确使用标题有助于搜索引擎优化。应该将 `<h1>` 用作主标题，以此类推。

Ensure that headings are used exclusively for headings and not just to create bold or large text. Proper use of headings improves SEO. Use `<h1>` for the main heading, and so on.

标题默认是居左的，可以调整居中、居右。

Headings are left-aligned by default, but they can be centered or right-aligned.

```html
<h1 align="center">
    一级
</h1>
```

这样就居中了，但是不推荐这么写。

This centers the heading, but it's not recommended to write it this way.

### 更推荐的做法

推荐使用CSS进行样式调整，而不是使用HTML的`align`属性。

It is recommended to use CSS for styling adjustments rather than using the HTML `align` attribute.

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .center {
            text-align: center;
        }
    </style>
</head>

<body>
    <h1 class="center">
        一级
    </h1>
</body>

</html>
```

### Explanation

在这个例子中，我们使用了CSS中的`text-align`属性将标题居中对齐。通过在`<h1>`标签中添加`class`属性并将其设置为`center`，我们可以将标题居中。

In this example, we use the `text-align` property in CSS to center-align the heading. By adding the `class` attribute to the `<h1>` tag and setting it to `center`, we can center the heading.

推荐使用CSS进行样式调整的原因有很多，主要包括以下几点：

### 分离内容与样式

使用CSS可以将内容与样式分离。HTML用于定义文档的结构和内容，而CSS则用于控制文档的外观和布局。通过分离内容和样式，可以更容易地维护和更新代码。

Using CSS separates content from style. HTML is used to define the structure and content of a document, while CSS controls the appearance and layout. This separation makes it easier to maintain and update the code.

### 可重用性

CSS样式可以在多个HTML元素中重用。通过定义一个CSS类，可以在文档的不同部分应用相同的样式，从而减少代码重复并提高效率。

CSS styles can be reused across multiple HTML elements. By defining a CSS class, the same style can be applied to different parts of the document, reducing code repetition and increasing efficiency.

### 灵活性

CSS提供了更强大的样式控制能力。通过CSS，可以实现更加复杂和精细的样式，例如渐变、阴影、动画等，而这些效果单靠HTML的属性是无法实现的。

CSS provides more powerful style control. With CSS, more complex and detailed styles can be achieved, such as gradients, shadows, and animations, which cannot be done with HTML attributes alone.

### 可维护性

将样式集中在一个CSS文件中，可以更容易地进行全局样式的调整。如果需要修改某个样式，只需更改CSS文件中的相关规则，而不需要在每个HTML文件中逐一修改。

Centralizing styles in a CSS file makes global style adjustments easier. If a style needs to be modified, it can be changed in the CSS file without having to update each HTML file individually.

### 遵循标准

现代的Web开发标准推荐使用CSS进行样式控制。使用CSS不仅符合最佳实践，还能确保网页在各种设备和浏览器中的一致性和兼容性。

Modern web development standards recommend using CSS for style control. Using CSS not only follows best practices but also ensures consistency and compatibility across different devices and browsers.

### 示例

以下是一个使用CSS进行样式控制的示例：

Example of using CSS for style control:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .center {
            text-align: center;
        }
    </style>
</head>

<body>
    <h1 class="center">
        一级标题
    </h1>
    <p class="center">
        这是一个段落。
    </p>
</body>

</html>
```

在这个示例中，我们定义了一个`.center`类，通过设置`text-align: center`来居中对齐文本。然后在需要居中的元素中添加`class="center"`即可。

In this example, we define a `.center` class that centers text by setting `text-align: center`. Then, we simply add `class="center"` to the elements that need to be centered.
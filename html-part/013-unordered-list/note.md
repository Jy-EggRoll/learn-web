# 列表

## 无序列表

无序列表用于展示一个没有特定顺序的项目列表，通常以圆点、方块等符号进行标记。

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>无序列表</title>
</head>

<body>
    <ul>
        <li>一个</li>
        <li>也是一个</li>
        <ul>
            <li>来个嵌套</li>
        </ul>
        <li>出嵌套</li>
    </ul>
</body>

</html>
```

**英文版**:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unordered List</title>
</head>

<body>
    <ul>
        <li>One</li>
        <li>Also one</li>
        <ul>
            <li>Nested item</li>
        </ul>
        <li>Exit nested</li>
    </ul>
</body>

</html>
```

## 无序列表的 `type`

`<ul>` 标签的 `type` 属性用于定义列表项的标记符号。可选值如下：

- `disc`：默认实心圆
- `circle`：空心圆
- `square`：小方块
- `none`：不显示任何标记

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>无序列表类型</title>
</head>

<body>
    <ul style="list-style-type: circle;">
        <li>圆圈</li>
        <li>圆圈</li>
    </ul>
</body>

</html>
```

**英文版**:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unordered List Type</title>
</head>

<body>
    <ul style="list-style-type: circle;">
        <li>Circle</li>
        <li>Circle</li>
    </ul>
</body>

</html>
```

## 无序列表嵌套

无序列表可以嵌套其他无序或有序列表，形成多级列表结构。

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>无序列表嵌套</title>
</head>

<body>
    <ul>
        <li>项一</li>
        <li>项二
            <ul>
                <li>子项一</li>
                <li>子项二</li>
            </ul>
        </li>
        <li>项三</li>
    </ul>
</body>

</html>
```

**英文版**:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nested Unordered List</title>
</head>

<body>
    <ul>
        <li>Item One</li>
        <li>Item Two
            <ul>
                <li>Sub-item One</li>
                <li>Sub-item Two</li>
            </ul>
        </li>
        <li>Item Three</li>
    </ul>
</body>

</html>
```

## 常见的应用场景

- **无序列表效果**：用于创建具有视觉层次结构的项目列表，如菜单、功能列表等。
- **页面导航效果**：常用于网页侧边栏或顶部导航条的项。

**英文版**:

- **Unordered List Effect**: Used to create project lists with visual hierarchy, such as menus or feature lists.
- **Page Navigation Effect**: Commonly used for items in a webpage sidebar or top navigation bar.

## 快捷键

在 Visual Studio Code (VSCode) 中，可以使用 Emmet 快捷键快速生成列表：

- **快捷键**: `ul>li*number` （`ol` 也可以使用）

例如，`ul>li*10` 将生成一个包含 10 个列表项的无序列表。

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>快捷键示例</title>
</head>

<body>
    <ul>
        <li>项 1</li>
        <li>项 2</li>
        <li>项 3</li>
        <li>项 4</li>
        <li>项 5</li>
        <li>项 6</li>
        <li>项 7</li>
        <li>项 8</li>
        <li>项 9</li>
        <li>项 10</li>
    </ul>
</body>

</html>
```

**英文版**:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emmet Shortcut Example</title>
</head>

<body>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
        <li>Item 5</li>
        <li>Item 6</li>
        <li>Item 7</li>
        <li>Item 8</li>
        <li>Item 9</li>
        <li>Item 10</li>
    </ul>
</body>

</html>
```
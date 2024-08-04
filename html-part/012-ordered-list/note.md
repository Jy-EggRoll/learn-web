# 列表

## 有序列表

有序列表用于展示一个有序的项目列表，通常以数字、字母或其他符号进行标记。

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>有序列表</title>
</head>

<body>
    <ol>
        <li>第一条。</li>
        <li>第二条。</li>
    </ol>
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
    <title>Ordered List</title>
</head>

<body>
    <ol>
        <li>First item.</li>
        <li>Second item.</li>
    </ol>
</body>

</html>
```

## `type` 属性

`<ol>` 标签可以使用 `type` 属性来改变列表项的标记方式：

- `1`：数字标号（默认）
- `a`：小写字母
- `A`：大写字母
- `i`：小写罗马数字
- `I`：大写罗马数字

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>有序列表类型</title>
</head>

<body>
    <ol type="A">
        <li>第一项</li>
        <li>第二项</li>
        <li>第三项</li>
    </ol>
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
    <title>Ordered List Type</title>
</head>

<body>
    <ol type="A">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
</body>

</html>
```

## 有序列表嵌套

有序列表可以嵌套其他有序或无序列表，形成多级列表结构。

**示例**:

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>有序列表嵌套</title>
</head>

<body>
    <ol>
        <li>天</li>
        <li>地</li>
        <li>人</li>
        <ol>
            <li>日</li>
            <li>月</li>
            <li>星</li>
        </ol>
    </ol>
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
    <title>Nested Ordered List</title>
</head>

<body>
    <ol>
        <li>Heaven</li>
        <li>Earth</li>
        <li>Human</li>
        <ol>
            <li>Sun</li>
            <li>Moon</li>
            <li>Star</li>
        </ol>
    </ol>
</body>

</html>
```
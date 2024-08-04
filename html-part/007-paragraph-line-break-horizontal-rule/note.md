# 段落、换行、水平线

## `<p>`段落

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <p>
        我是一个段落。
    </p>
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
    <title>Document</title>
</head>

<body>
    <p>
        I am a paragraph.
    </p>
</body>

</html>
```

## `<br>`换行

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <p>
        我是<br>一个段落（不产生新段落的换行）。
    </p>
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
    <title>Document</title>
</head>

<body>
    <p>
        I am<br> a paragraph (line break without creating a new paragraph).
    </p>
</body>

</html>
```

## `<hr>`水平线

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        hr {
            border: none;
            height: 2px;
            background-color: red;
            width: 50%;
            margin: 20px 0;
        }
    </style>
</head>

<body>
    <p>
        我是一个段落。
    </p>
    <hr>
    <p>
        我是另一个段落。
    </p>
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
    <title>Document</title>
    <style>
        hr {
            border: none;
            height: 2px;
            background-color: red;
            width: 50%;
            margin: 20px 0;
        }
    </style>
</head>

<body>
    <p>
        I am a paragraph.
    </p>
    <hr>
    <p>
        I am another paragraph.
    </p>
</body>

</html>
```

---

这样可以确保符合现代的 HTML5 标准，并且提供了用 CSS 控制 `<hr>` 样式的示例。
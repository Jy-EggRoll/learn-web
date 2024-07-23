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

## `<hr>`水平线

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
    <hr>
    <p>
        我是另一个段落。
    </p>
</body>

</html>
```

`hr`的一些属性；
1. color
2. width
3. size
4. align

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
    <hr color="red">
    <p>
        我是另一个段落。
    </p>
</body>

</html>
```

红色的水平线。
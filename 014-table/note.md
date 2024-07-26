# 表格

## 表格的展示效果

### 表格的组成和特点

组成：行、列、单元格

单元格特点：同行等高，同列等宽

### 表格标签

表格：`<table>`

行：`<tr>`

列：`<td>`

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <table>
        <tr>
            <td>一行一列</td>
            <td>一行二列</td>
        </tr>
        <tr>
            <td>二行一列</td>
            <td>二行二列</td>
        </tr>
    </table>
</body>

</html>
```

VSCode中可以用快捷键：`table>tr*数量>td*数量{内容}`来实现快速创建表格。

## 表格的属性

- border：边框
- width：宽度
- height：高度

但是不推荐使用属性的形式调节表格的样式。
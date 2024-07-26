# 表格单元格合并

## 合并方式

- 水平合并`colspan`
- 垂直合并`rowspan`

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <table border="2">
        <tr>
            <td>cell1</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell5</td>
        </tr>
        <tr>
            <td colspan="2">cell6 and cell7</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell10</td>
        </tr>
        <tr>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
            <td rowspan="2">cell15 and cell20</td>
        </tr>
        <tr>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
        </tr>
        <tr>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
            <td>cell</td>
        </tr>
    </table>
</body>

</html>
```

### 默认：

- 水平合并：保留左边，删除右边
- 垂直合并：保留下边，删除上边


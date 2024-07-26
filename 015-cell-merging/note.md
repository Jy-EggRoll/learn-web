# 表格单元格合并

## 合并方式

- 水平合并 `colspan`  
  Horizontal merge `colspan`  

- 垂直合并 `rowspan`  
  Vertical merge `rowspan`  

`colspan` 属性用于在水平（列）上合并单元格，`rowspan` 属性用于在垂直（行）上合并单元格。通过这些属性，可以创建更复杂的表格布局。  
The `colspan` attribute is used to merge cells horizontally (across columns), while the `rowspan` attribute is used to merge cells vertically (across rows). These attributes allow you to create more complex table layouts.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table Merge Example</title>
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

在这个示例中：
- `cell6 and cell7` 单元格使用了 `colspan="2"`，合并了两列。
- `cell15 and cell20` 单元格使用了 `rowspan="2"`，合并了两行。

In this example:
- The cell with text `cell6 and cell7` uses `colspan="2"` to merge two columns.
- The cell with text `cell15 and cell20` uses `rowspan="2"` to merge two rows.

### 默认：
水平合并：保留左边，删除右边
Default horizontal merge: Retain the left side, remove the right side

垂直合并：保留上边，删除下边
Default vertical merge: Retain the top side, remove the bottom side

垂直合并时，表格会保留合并区域的上侧的单元格内容，而删除合并区域的下侧的单元格内容。
When merging cells vertically, the table retains the content of the cells on the top side of the merge area, while removing the content of the cells on the bottom side of the merge area.
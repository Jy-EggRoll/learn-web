# 表格

## 表格的展示效果

### 表格的组成和特点

组成：行、列、单元格  
Composition: Rows, columns, and cells  

表格由行(`<tr>`)、列(`<td>`)和单元格组成。每个单元格可以包含文本、图片或其他HTML元素。同行的单元格通常具有相同的高度，而同列的单元格具有相同的宽度。  
A table consists of rows (`<tr>`), columns (`<td>`), and cells. Each cell can contain text, images, or other HTML elements. Cells in the same row usually have the same height, while cells in the same column have the same width.

### 表格标签

表格：`<table>`  
Table: `<table>`  

行：`<tr>`  
Row: `<tr>`  

列：`<td>`  
Column: `<td>`  

`<table>` 标签定义一个表格。`<tr>` 标签定义表格的行，`<td>` 标签定义行中的单元格。可以在单元格中放置各种内容，如文本、图像或其他HTML元素。  
The `<table>` tag defines a table. The `<tr>` tag defines a row in the table, and the `<td>` tag defines a cell in that row. Various content such as text, images, or other HTML elements can be placed inside the cells.

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表格示例</title>
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

在这个示例中，我们创建了一个包含两行两列的简单表格。每个单元格内包含了一些文本。  
In this example, we have created a simple table with two rows and two columns. Each cell contains some text.

VSCode中可以用快捷键：`table>tr*行数>td*列数{内容}`来实现快速创建表格。  
In VSCode, you can use the shortcut: `table>tr*number of rows>td*number of columns{content}` to quickly create tables.

## 表格的属性

- `border`：边框  
- `border`: Border  

- `width`：宽度  
- `width`: Width  

- `height`：高度  
- `height`: Height  

这些属性可以直接在`<table>`标签中使用来设置表格的边框、宽度和高度。例如，`<table border="1">`会为表格添加一个边框。  
These attributes can be used directly in the `<table>` tag to set the table’s border, width, and height. For example, `<table border="1">` will add a border to the table.

然而，更推荐使用CSS来控制表格的样式，因为CSS提供了更多的样式选择和灵活性。  
However, it is better to use CSS to style tables, as CSS offers more styling options and flexibility.
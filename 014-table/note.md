# 表格

HTML中的表格是一种用来组织和显示数据的结构。表格是通过`<table>`标签创建的，包含了表头`<thead>`、表身`<tbody>`和表尾`<tfoot>`，其中每一行用`<tr>`标签表示，每个单元格用`<td>`（表数据）或`<th>`（表头）标签表示。

举个例子：

```html
<table>
  <thead>
    <tr>
      <th>姓名</th>
      <th>年龄</th>
      <th>城市</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>张三</td>
      <td>25</td>
      <td>北京</td>
    </tr>
    <tr>
      <td>李四</td>
      <td>30</td>
      <td>上海</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">总计</td>
    </tr>
  </tfoot>
</table>
```

在这个例子中，表格包含了表头（姓名、年龄、城市）、两行数据（张三和李四）以及一个表尾（总计）。

Tables in HTML are used to organize and display data in a structured format. They are created using the `<table>` tag and typically include a header (`<thead>`), a body (`<tbody>`), and a footer (`<tfoot>`), with each row represented by a `<tr>` tag and each cell by a `<td>` (table data) or `<th>` (table header) tag.

For example:

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Zhang San</td>
      <td>25</td>
      <td>Beijing</td>
    </tr>
    <tr>
      <td>Li Si</td>
      <td>30</td>
      <td>Shanghai</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">Total</td>
    </tr>
  </tfoot>
</table>
```

In this example, the table includes headers (Name, Age, City), two rows of data (Zhang San and Li Si), and a footer (Total).

表格标签的使用使数据更加清晰和有条理，特别是在展示大量数据时非常有用。  
The use of table tags makes data clearer and more organized, which is especially useful when displaying large amounts of data.
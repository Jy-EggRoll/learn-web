# 表单

表单在网页中用来给用户填写信息。比如登录注册、搜索框等。  
Forms are used on web pages to allow users to input information, such as for login, registration, search boxes, etc.

有用户输入的地方基本就会用到表单。  
Forms are used wherever user input is required.

表单是由容器和控件组成的，一个表单一般应该包含用户填写信息的输入框、提交按钮等。这些输入框、按钮叫控件，表单就是容器，容器可以容纳各种各样的控件。  
A form consists of a container and controls. A typical form includes input fields for users to enter information, submit buttons, etc. These input fields and buttons are called controls, and the form acts as the container that can hold various controls.

## 属性说明（先了解）

```html
<form action="" method="" name=""></form>
```

- `action`：服务器地址  
  `action`: Server address  

  `action` 属性指定了表单数据提交到的服务器地址。  
  The `action` attribute specifies the URL to which the form data will be submitted.

- `name`：表单名称（识别不同的表单）  
  `name`: Form name (to identify different forms)  

  `name` 属性为表单定义一个名称，用于标识和引用不同的表单。  
  The `name` attribute gives the form a name to identify and reference different forms.

- `method`：数据提交方式（get|post）  
  `method`: Data submission method (`get`|`post`)  

  `method` 属性指定了表单数据提交的方式。`get` 方法会将数据附加到 URL 后面，而 `post` 方法则将数据放在请求体中。  
  The `method` attribute specifies how form data is submitted. The `get` method appends data to the URL, while the `post` method includes data in the request body.

## 表单元素

- 表单标签  
  Form tag  

  表单标签 `<form>` 是定义表单的基础。它包含所有表单控件，并且可以通过 `action` 和 `method` 属性指定数据提交的行为。  
  The `<form>` tag defines the form. It contains all form controls and can specify how data is submitted using the `action` and `method` attributes.

- 表单域  
  Form fields  

  表单域是用户输入数据的地方，包括文本框、下拉菜单、单选按钮等。常见的表单域标签包括 `<input>`、`<textarea>`、`<select>` 和 `<button>`。  
  Form fields are where users input data, including text boxes, drop-down menus, radio buttons, etc. Common form field tags include `<input>`, `<textarea>`, `<select>`, and `<button>`.

- 表单按钮  
  Form buttons  

  表单按钮用于提交表单数据或执行其他操作。主要的表单按钮标签是 `<button>` 和 `<input type="submit">`。  
  Form buttons are used to submit form data or perform other actions. The primary form button tags are `<button>` and `<input type="submit">`.
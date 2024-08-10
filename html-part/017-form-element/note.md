# 表单元素

## 文本框

文本框用于让用户输入单行文本信息。通常使用 `<input type="text">` 标签来创建。  
Text boxes are used to allow users to input single-line text. They are typically created using the `<input type="text">` tag.

## 密码框

密码框用于让用户输入密码。密码框中的文本会被掩盖，以保护用户隐私。使用 `<input type="password">` 标签来创建。  
Password boxes are used for users to enter passwords. The text in a password box is masked to protect user privacy. This is created using the `<input type="password">` tag.

## 提交按钮

提交按钮用于将表单数据提交给服务器。使用 `<input type="submit">` 或 `<button type="submit">` 标签来创建。  
Submit buttons are used to send form data to the server. They are created using the `<input type="submit">` or `<button type="submit">` tag.

```html
<!DOCTYPE html>
<html lang="zh">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>表单示例</title>
</head>

<body>
    <form>
        <input type="text" placeholder="请输入文本">
        <input type="submit" value="提交">
    </form>
    <form>
        用户名：<input type="text" placeholder="请输入用户名">
        <br>
        生日：<input type="text" placeholder="请输入生日">
    </form>
    <form>
        用户名：<input type="text" placeholder="请输入用户名">
        <br>
        密码：<input type="password" placeholder="请输入密码">
        <input type="submit" value="登录">
    </form>
</body>

</html>
```

在这个示例中：
- 第一个表单包含一个文本框和一个提交按钮。`<input type="text">` 用于输入文本，`<input type="submit">` 用于提交表单数据。
- 第二个表单有两个文本框，分别用于输入用户名和生日。
- 第三个表单包含一个文本框用于输入用户名和一个密码框用于输入密码，此外还有一个提交按钮用于登录。

In this example:
- The first form includes a text box and a submit button. `<input type="text">` is used for text input, and `<input type="submit">` is used to submit the form data.
- The second form has two text boxes for entering a username and a birthday.
- The third form includes a text box for entering a username and a password box for entering a password, along with a submit button for login.


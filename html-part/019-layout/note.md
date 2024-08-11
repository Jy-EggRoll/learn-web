# 布局

网页布局对于改善网页的外观是非常重要的。

```html
<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <title>菜鸟教程</title>
</head>

<body>
    <div id="container" style="width: 500px;">
        <div id="header" style="background-color: #FFA500;">
            <h1 style="margin-bottom: 0;">
                主要的网页标题
            </h1>
        </div>
        <div id="menu" style="background-color: #FFD700; height: 200px; width: 100px; float: left;">
            <b>
                菜单<br>
            </b>
            HTML<br>
            CSS<br>
            JavaScript
        </div>
        <div id="content" style="background-color: #EEEEEE; height: 200px; width: 400px; float: left;">
            内容在这里。
        </div>
        <div id="footer" style="background-color: #FFA500; clear: both; text-align: center;">
            版权 © 菜鸟教程
        </div>
    </div>
</body>

</html>
```
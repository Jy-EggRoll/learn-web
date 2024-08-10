# CSS的引入方式

## 内联样式

```html
<p style="color:red;">这是一个红色的段落。</p>
```

不推荐这样写。

## 内部样式表

```html
<!DOCTYPE html>
<html>
<head>
	<title>内部样式表</title>
	<style>
		p {
			color: red;
		}
	</style>
</head>
<body>
	<p>这是一个红色的段落。</p>
</body>
</html>
```

1. 在`head`标签中添加一个`style`标签。
2. 在`style`标签中编写CSS样式。
3. 在HTML文档中使用样式。

也不推荐这么使用，这是因为如果有多个页面使用同一个样式，就需要在每个页面都添加样式，这样会导致代码冗余。

## 外部样式

1. 创建一个`.css`文件。
2. 在`head`标签中添加一个`link`标签。
3. 设置`link`标签的`href`属性为`.css`文件的路径。

这样，就可以在多个页面中使用同一个样式。整个站点可以有统一的风格。
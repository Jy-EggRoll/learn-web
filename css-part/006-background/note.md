# CSS背景属性

## background-color

设置背景颜色：

在HTML中有一个`<div>`元素

```html
<div class="box"></div>
```

CSS中设置背景颜色：

```css
.box {
  background-color: #f2f2f2;
}
```

或者直接写


```css
div {
    background-color: #f2f2f2;
}
```

## background-image

默认情况下，背景图片从元素的左上角开始显示。如果容器大于图片，图片默认重复以填充整个容器。如果容器小于图片，那么默认情况下图像只有一部分可以显示出来。


```css
.box {
  background-image: url("image.jpg");
}
```

## background-repeat

设置背景图片的重复方式：

- repeat：背景图片在水平和垂直方向上都重复。
- repeat-x：背景图片在水平方向上重复。
- repeat-y：背景图片在垂直方向上重复。
- no-repeat：背景图片不重复。

```css
.box {
  background-image: url("image.jpg");
  background-repeat: no-repeat;
}
```

## background-size

设置背景图片的大小：

- 绝对像素
- 百分比
- cover：背景图片完全覆盖容器。
- contain：背景图片尽可能完整地包含在容器中。

```css
.box {
  background-image: url("image.jpg");
  background-size: cover;
}
```

## background-position

设置渲染的起始位置：

- 绝对像素位置
- 百分比位置
- 预定义位置：top、center、bottom、left、right等
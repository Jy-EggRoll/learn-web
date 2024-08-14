# 圆角

圆角也是CSS3的新特性，可以让元素的边框变得圆滑，看起来更加美观。

## 用法

1. 设置元素的border-radius属性，值为半径值。

```css
div {
  border-radius: 10px; /* 圆角半径为10px */
}
```

2. 还可以设置四个角的圆角半径，分别为左上、右上、右下、左下。


```css
div {
  border-top-left-radius: 10px; /* 左上角的圆角半径为10px */
  border-top-right-radius: 5px; /* 右上角的圆角半径为5px */
  border-bottom-right-radius: 15px; /* 右下角的圆角半径为15px */
  border-bottom-left-radius: 10px; /* 左下角的圆角半径为10px */
}
```
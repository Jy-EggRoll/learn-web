# 字体属性

CSS的字体属性用来定义字体的样式、颜色、大小、粗细等。

## color

规定文本颜色：

```css
p {
    color: red;
    color: #ff0000;
    color: rgb(255, 0, 0);
    
    /* 透明度rgb */
    color: rgba(255, 0, 0, 0.5);
}
```

## font-size

规定字体大小：

```css
p {
    font-size: 16px;
}
```

## font-weight

数字越大，字体越粗：

```css
p {
    font-weight: normal; /* 正常 */
    font-weight: bold; /* 加粗 */
    font-weight: 100; /* 细体 */
    font-weight: 900; /* 粗体 */
}
```

## font-style

1. normal：正常
2. italic：斜体

## font-family

指定元素的字体：

```css
p {
    font-family: Arial, sans-serif; /* 优先使用 Arial，如果 Arial 不存在，则使用 sans-serif */
}
```
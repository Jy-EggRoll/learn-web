# 文档流

## 底边对齐

![alt text](image.png)

行内元素默认是底边对齐的。

## 空格折叠

不管输入多少个空格，都会折叠为一个。

## 元素无空隙

换行输入两个`<img>`标签，图片之间会产生空隙。如果在一行内输入两个`<img>`标签，就不会产生空隙。

## 如何避免这些问题？脱离文档流

1. 浮动
2. 绝对定位
3. 固定定位
# 弹性盒子模型

弹性盒子是CSS3的新特性，目前仅作了解。

## 基本概念

1. 容器（container）：一个容器可以包含多个项目（item）。
2. 项目（item）：一个项目可以是任何HTML元素，包括块级元素、行内元素、表格单元格等。
3. 主轴（main axis）：主轴是项目沿着的方向，默认是水平方向。
4. 交叉轴（cross axis）：交叉轴是主轴垂直方向的方向。

## 使用方法

1. display: flex;：将容器设置为弹性盒子。
2. flex-direction: row | row-reverse | column | column-reverse;：设置主轴的方向。
3. justify-content: flex-start | flex-end | center | space-between | space-around;：设置主轴上项目的对齐方式。
4. align-items: flex-start | flex-end | center | baseline | stretch;：设置交叉轴上项目的对齐方式。
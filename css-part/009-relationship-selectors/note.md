# 关系选择器

# 关系选择器分类

1. 后代选择器
2. 子代选择器
3. 相邻兄弟选择器
4. 通用兄弟选择器

## 后代选择器

### 定义

后代选择器（Descendant Selector）：选择作为某元素后代的元素。

### 语法

```css
ancestor descendant {
  /* 样式 */
}
```

### 示例

```html
<div class="parent">
  <p class="child">Hello World</p>
</div>
```

```css
.parent .child {
  color: red;
}
```

## 子代选择器

### 定义

子代选择器（Child Selector）：选择作为某元素直接子元素的元素。

### 语法

```css
parent > child {
  /* 样式 */
}
```

### 示例

```html
<div class="parent">
  <p class="child">Hello World</p>
</div>
```

```css
.parent >.child {
  color: red;
}
```

## 相邻兄弟选择器

### 定义

相邻兄弟选择器（Adjacent Sibling Selector）：选择紧接着某元素的同级元素。

### 语法

```css
element + adjacent {
  /* 样式 */
}
```

### 示例

```html
<div class="parent">
  <p class="child1">Hello</p>
  <p class="child2">World</p>
</div>
```

```css
.parent p + p {
  color: red;
}
```

## 通用兄弟选择器

### 定义

通用兄弟选择器（General Sibling Selector）：选择所有作为某元素的同级元素。

### 语法

```css
element ~ sibling {
  /* 样式 */
}
```

### 示例

```html
<div class="parent">
  <p class="child1">Hello</p>
  <p class="child2">World</p>
  <span class="sibling">!</span>
</div>
```

```css
.parent p ~ span {
  color: red;
}
```
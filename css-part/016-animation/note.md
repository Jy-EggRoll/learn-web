# CSS动画

CSS动画是CSS3的新特性，可以实现一种效果到另一种效果的平滑过渡。优点是性能高。

## 基本语法

```css
/* 选择器 */
@keyframes animationName {
  /* 动画属性 */
  from {   /* 开始状态 */
    /* 动画属性 */
  }
  to {     /* 结束状态 */
    /* 动画属性 */
  }
}

/* 触发动画 */
.element {
  animation-name: animationName;
  animation-duration: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
  animation-timing-function: ease-in-out;
  animation-fill-mode: both;
}
```

## 动画属性

- `animation-name`：动画名称，定义在`@keyframes`规则中。
- `animation-duration`：动画持续时间，单位为秒。
- `animation-iteration-count`：动画重复次数，可以是数字或infinite。
- `animation-direction`：动画播放方向，可以是normal、reverse、alternate。
- `animation-timing-function`：动画速度曲线，可以是linear、ease、ease-in、ease-out、ease-in-out、cubic-bezier(x1, y1, x2, y2)。
- `animation-fill-mode`：动画结束后状态，可以是none、forwards、backwards、both。
---
title: "CSSFlexbox: 使用align-self属性"
date: 2019-03-21
---
### `align-self`属性允许你单独调整每个项目得对齐方式，而不是一次性设置他们。align-self能覆盖align-items属性设置的任何值。
```css
#box-container {
  display: flex;
  height: 500px;
}
#box-1 {
  background-color: blue;
  height: 200px;
  width: 200px;
  align-self: center;
}
#box-2 {
  background-color: red;
  height: 200px;
  width: 200px;
  align-self: flex-end;
}
```

```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"> </div>
</div>
```

